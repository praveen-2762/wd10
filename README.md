<!DOCTYPE html>
<html lang="en">
  <head>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT"
      crossorigin="anonymous"
    />

    <script src="index.js" defer></script>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <div class="container">
      <h1 class="display-3 mt-4">praveen Capstone Project Form</h1>
      <hr />
      <form action="" id="form" onsubmit="sConsole(event)">
        <input
          class="form-control mt-2"
          placeholder="Name"
          type="text"
          name="Name"
          id="name"
        />
        <input
          class="form-control mt-2"
          placeholder="Email"
          type="email"
          name="Email"
          id="email"
        />
        <input
          class="form-control mt-2"
          placeholder="Password"
          type="password"
          name="Password"
          id="password"
        />
        <input
          class="form-control mt-2"
          placeholder="Dob"
          type="date"
          name="Dob"
          id="dob"
        />
        <input
          class="form-check-input mt-2"
          type="checkbox"
          name="Accepted terms?"
          id="accept"
        />
        <button class="btn btn-primary btn-sm mt-2" type="submit">
          Submit
        </button>
      </form>
      <table class="table mt-2" id="table_id">
        <thead>
          <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Password</th>
            <th>Dob</th>
            <th>Accept</th>
          </tr>
        </thead>
        <tbody id="table_body"></tbody>
      </table>
    </div>
  </body>
</html>
