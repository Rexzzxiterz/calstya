// ANIMASI SCROLL
const elements = document.querySelectorAll(".fade");

const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add("show");
    }
  });
});

elements.forEach(el => observer.observe(el));

// MUSIC CONTROL
const music = document.getElementById("music");
const btn = document.getElementById("musicBtn");

btn.addEventListener("click", () => {
  if (music.paused) {
    music.play();
    btn.innerText = "Pause Music";
  } else {
    music.pause();
    btn.innerText = "Play Music";
  }
});
