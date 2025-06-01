# pha-team-page

A page designed for Frontend Facilitator and Interns

# How to contribute

1. Clone the Repository . Repository Link here: [pha-team-page](https://github.com/Ariyibi-Baseet/pha-team-page.git)

2. create a branch i.e a branchname using your name
   Example: run `git checkout -b branchname`

3. Add your image inside img folder in assets folder.

4. Duplicate the element with a class of "profile-card" with your information. Example Below:

```html
<div class="profile-card">
  <img
    src="assets/img/your image here.jpg"
    class="profile-img"
    alt="your name here"
  />
  <div class="content">
    <h1 class="name">Your Name.Initial</h1>
    <p class="stack">Your Stack</p>
    <div class="social-link">
      <a href="your linkedin profile link"> <i class="bi bi-linkedin"></i></a>
      <a href="your github profile link"> <i class="bi bi-github"></i> </a>
      <a href="your twitter profile link"> <i class="bi bi-twitter-x"></i> </a>
    </div>
  </div>
</div>
```

5. run `git add .`
6. run `git commit -m "added my profile card"`
7. Your
   are done, the next thing you need to do is to push your code back to the remote
   repository by running `git push origin your branchname`
8. click on the pull request link to make a pull request
