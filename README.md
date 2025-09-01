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


<button class="prev">
  <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="white" viewBox="0 0 24 24">
    <path d="M15 18l-6-6 6-6"/>
  </svg>
</button>

<button class="next">
  <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="white" viewBox="0 0 24 24">
    <path d="M9 6l6 6-6 6"/>
  </svg>
</button>
