- 👋 Hi, I’m @Ughh-Sarthak
- 👀 I’m interested in web development
- 🌱 I’m currently learning Java
- 💞️ I’m looking to collaborate on any project to gain experience
- 📫 How to reach me :sarthakdeshmukh009@gmail.com

- 
<!---
Ughh-Sarthak/Ughh-Sarthak is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>About Rohit Sharma</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Rohit Sharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link active" href="#">Stats</a></li> <!-- both active -->
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <div class="row align-items-center">
      <div class="col-md-4 text-center">
        <img src="rohit.jpeg" alt="Rohit Sharma" class="rounded-circle img-fluid border border-3 border-primary" />
      </div>
      <div class="col-md-8">
        <h1 class="mb-3">Rohit Sharma</h1>
        <h5 class="text-secondary mb-4">Indian Cricketer</h5>
        <p>Rohit Sharma is one of India's finest batsmen, known for his elegant stroke play and powerful hitting. He has multiple records in international cricket, including highest individual ODI score.</p>
        <a href="#" class="btn btn-primary mt-3">Follow Rohit</a>
      </div>
    </div>

    <hr class="my-5" />

    <div class="row">
      <div class="col-md-6">
        <h3>Career Highlights</h3>
        <ul>
          <li>First player to score three double centuries in ODIs.</li>
          <li>Captain of Mumbai Indians IPL team with multiple titles.</li>
          <li>Over 9000 ODI runs with an average above 48.</li>
          <li>Known as the 'Hitman' for his powerful batting style.</li>
        </ul>
      </div>
      <div class="col-md-6">
        <h3>Key Records</h3>
        <table class="table table-striped">
          <tbody>
            <tr>
              <th scope="row">Highest ODI Score</th>
              <td>264 runs</td>
            </tr>
            <tr>
              <th scope="row">Most T20 International Centuries</th>
              <td>4</td>
            </tr>
            <tr>
              <th scope="row">IPL Runs</th>
              <td>6000+ runs</td>
            </tr>
            <tr>
              <th scope="row">International Centuries</th>
              <td>29+</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <div class="text-center mt-5">
      <h4>Quick Stats</h4>
      <div class="row justify-content-center">
        <div class="col-6 col-md-3 mb-3">
          <div class="p-3 bg-primary text-white rounded">
            <h5>ODI Matches</h5>
            <p>227</p>
          </div>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <div class="p-3 bg-success text-white rounded">
            <h5>T20I Matches</h5>
            <p>115</p>
          </div>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <div class="p-3 bg-warning text-dark rounded">
            <h5>Test Matches</h5>
            <p>46</p>
          </div>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <div class="p-3 bg-info text-white rounded">
            <h5>IPL Titles</h5>
            <p>5</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
