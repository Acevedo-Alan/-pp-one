# -pp-one

HOLA ALAN KETAI ASIENDO OIE


<div id="rating"></div>

<script>
  function renderStars(rating) {
    const fullStar = "★";
    const emptyStar = "☆";
    let stars = "";

    for (let i = 1; i <= 5; i++) {
      stars += i <= rating ? fullStar : emptyStar;
    }
    return stars;
  }

  document.getElementById("rating").innerHTML = renderStars(3);
</script>
