# Jang-lupa-folow
instagram

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reicksann Instagram</title>
<style>
body {
  background: #111;
  color: white;
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.profile {
  text-align: center;
}
.instagram {
  width: 100px;
  height: 100px;
  border-radius: 28px;
  background: linear-gradient(45deg,
    #feda75, #fa7e1e, #d62976,
    #962fbf, #4f5bd5);
  display: flex;
  justify-content: center;
  align-items: center;
  margin: auto;
}
.camera {
  width: 48px;
  height: 48px;
  border: 5px solid white;
  border-radius: 15px;
  position: relative;
}
.camera::before {
  content: "";
  position: absolute;
  width: 18px;
  height: 18px;
  border: 4px solid white;
  border-radius: 50%;
  top: 11px;
  left: 11px;
}
.camera::after {
  content: "";
  position: absolute;
  width: 6px;
  height: 6px;
  background: white;
  border-radius: 50%;
  top: 5px;
  right: 5px;
}
h2 {
  letter-spacing: 4px;
}
</style>
</head>
<body>
<div class="profile">
  <div class="instagram">
    <div class="camera"></div>
  </div>
  <h2>REICKSANN</h2>
  <p>Instagram Profile</p>
</div>
</body>
</html>
