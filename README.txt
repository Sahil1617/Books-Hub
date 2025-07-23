<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Books Hub - Library Management System</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Bootstrap CSS CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      padding-top: 3rem;
      padding-bottom: 3rem;
      background-color: #f8f9fa;
    }
    .feature-icon {
      font-size: 1.5rem;
      color: #0d6efd;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="text-center mb-5">
    <h1 class="display-4 fw-bold">📚 Books Hub</h1>
    <p class="lead">A Complete Library Management System using PHP, MySQL, HTML, CSS, and Bootstrap</p>
  </div>

  <section class="mb-5">
    <h2>🛠️ Technologies Used</h2>
    <ul class="list-group list-group-flush">
      <li class="list-group-item">PHP (Backend Logic)</li>
      <li class="list-group-item">MySQL (Database)</li>
      <li class="list-group-item">HTML & CSS (Frontend Design)</li>
      <li class="list-group-item">Bootstrap (Responsive Layout)</li>
      <li class="list-group-item">XAMPP Server (Local Development)</li>
    </ul>
  </section>

  <section class="mb-5">
    <h2>✨ Features</h2>

    <div class="card mb-4">
      <div class="card-header bg-primary text-white">🧑‍💼 Admin Panel</div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">➕ Add / ✏️ Edit / ❌ Delete Books</li>
        <li class="list-group-item">👥 Manage Users</li>
        <li class="list-group-item">📖 Issue and Return Books</li>
        <li class="list-group-item">📄 View Issued Book Reports</li>
      </ul>
    </div>

    <div class="card mb-4">
      <div class="card-header bg-success text-white">👤 User Panel</div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">🔍 Search and View Books</li>
        <li class="list-group-item">📬 Request to Borrow Books</li>
        <li class="list-group-item">📦 Track Issued Books</li>
      </ul>
    </div>

    <div class="card mb-4">
      <div class="card-header bg-warning text-dark">🔒 Authentication System</div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">🔐 Secure Login for Admin and Users</li>
        <li class="list-group-item">🕒 Session Management</li>
      </ul>
    </div>

    <div class="card mb-4">
      <div class="card-header bg-info text-white">📊 Dashboard</div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">📚 Overview of Total Books, Issued Books, and Users</li>
        <li class="list-group-item">📱 Responsive and Mobile-friendly Interface</li>
      </ul>
    </div>
  </section>

  <section class="mb-5">
    <h2>📂 Installation Guide</h2>
    <ol class="list-group list-group-numbered">
      <li class="list-group-item">Download and install <strong>XAMPP</strong> from <a href="https://www.apachefriends.org/index.html" target="_blank">apachefriends.org</a>.</li>
      <li class="list-group-item">Start <strong>Apache</strong> and <strong>MySQL</strong> from the XAMPP Control Panel.</li>
      <li class="list-group-item">Place the project folder inside <code>htdocs</code> directory (e.g. <code>C:\xampp\htdocs\books-hub</code>).</li>
      <li class="list-group-item">Import the <code>books_hub.sql</code> file into phpMyAdmin to set up the database.</li>
      <li class="list-group-item">Update database connection settings in <code>config.php</code>.</li>
      <li class="list-group-item">Open the project in your browser: <br><code>http://localhost/books-hub</code></li>
    </ol>
  </section>

  <section class="mb-5">
    <h2>📸 Screenshots</h2>
    <p><em>(Add your screenshots here for better visual presentation)</em></p>
  </section>

  <footer class="text-center mt-5">
    <p class="text-muted">© 2025 Books Hub | Developed using PHP & MySQL</p>
  </footer>
</div>

</body>
</html>
