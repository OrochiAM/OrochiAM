<img src="https://orochiam.github.io/PROJEKTNI-ZADATAK-COOLINAR/images/milic.png" width="350px" class="milic">


<script src="https://cdn.jsdelivr.net/npm/gsap@3.12.5/dist/gsap.min.js"></script>

<script type="text/javascript">
  const hover = gsap.timeline({ repeat: -1 });

hover
  .to('.milic', {
    y: '-=30',
    ease: Sine.easeInOut,
    duration: 2,
  })
  .to('.milic', {
    y: '+=30',
    ease: Sine.easeInOut,
    duration: 2,
  })
  .to('.milic', {
    y: '-=20',
    ease: Sine.easeInOut,
    duration: 2,
  })
  .to('.milic', {
    y: '+=20',
    ease: Sine.easeInOut,
    duration: 2,
  })
  .to('.milic', {
    y: '-=50',
    ease: Sine.easeInOut,
    duration: 2,
  })
  .to('.milic', {
    y: '+=50',
    ease: Sine.easeInOut,
    duration: 2,
  });
</script>

