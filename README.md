body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  padding: 10px 20px;
}

#header-logo {
  height: 40px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

#promo-banner {
  position: relative;
  text-align: center;
  color: white;
}

#promo-banner img {
  width: 100%;
  height: auto;
}

.promo-description {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: rgba(0, 0, 0, 0.5);
  padding: 20px;
  border-radius: 10px;
}

#features {
  display: flex;
  justify-content: space-around;
  margin: 20px 0;
}

.feature {
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 10px;
  overflow: hidden;
  text-align: center;
  width: 30%;
}

.feature img {
  width: 100%;
  height: auto;
}

.feature-description {
  padding: 20px;
}

.feature-description a {
  display: inline-block;
  margin-top: 10px;
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px 0;
  position: relative;
}

#footer-logo {
  height: 40px;
}

#scrollToTopBtn {
  position: fixed;
  bottom: 20px;
  right: 20px;
  padding: 10px;
  background-color: #333;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

#scrollToTopBtn:hover {
  background-color: #555;
}
