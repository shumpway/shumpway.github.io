# shumpway.github.io
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Shump</title>
    <style>
    body {
  font-family: 'Poppins', sans-serif;
  color: #000000;
  background-color: #ffffff;
}

.layout_padding {
  padding-top: 120px;
  padding-bottom: 120px;
}

.layout_padding2 {
  padding-top: 45px;
  padding-bottom: 45px;
}

.layout_padding2-top {
  padding-top: 45px;
}

.layout_padding2-bottom {
  padding-bottom: 45px;
}

.layout_padding-top {
  padding-top: 120px;
}

.layout_padding-bottom {
  padding-bottom: 120px;
}

.heading_container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  text-align: center;
}

.heading_container h2 {
  font-weight: bold;
  position: relative;
  padding-bottom: 5px;
  text-transform: uppercase;
}

.heading_container h2::before {
  content: "";
  position: absolute;
  bottom: 0;
  left: 50%;
  width: 55px;
  height: 5px;
  background-color: #ff2953;
  -webkit-transform: translateX(-50%);
          transform: translateX(-50%);
}

/*header section*/
.hero_area {
  height: 100vh;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  background-image: url(../images/hero-bg.jpg);
  background-size: cover;
  background-attachment: fixed;
}

.sub_page .hero_area {
  height: auto;
}

.sub_page .who_section.layout_padding {
  padding-top: 0;
}

.hero_area.sub_pages {
  height: auto;
}

.header_section .container-fluid {
  padding-right: 25px;
  padding-left: 25px;
}

.header_section .nav_container {
  margin: 0 auto;
}

.custom_nav-container.navbar-expand-lg .navbar-nav .nav-item .nav-link {
  margin: 10px 30px;
  padding: 0;
  padding-bottom: 3px;
  color: #ffffff;
  text-align: center;
  position: relative;
  text-transform: uppercase;
  font-size: 15px;
}

.custom_nav-container.navbar-expand-lg .navbar-nav .nav-item .nav-link::after {
  display: none;
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 3px;
  border-radius: 5px;
  background-color: #ffffff;
}

.custom_nav-container.navbar-expand-lg .navbar-nav .nav-item.active a::after, .custom_nav-container.navbar-expand-lg .navbar-nav .nav-item:hover a::after {
  display: block;
  background-color: #ff2953;
}

a,
a:hover,
a:focus {
  text-decoration: none;
}

a:hover,
a:focus {
  color: initial;
}

.btn,
.btn:focus {
  outline: none !important;
  -webkit-box-shadow: none;
          box-shadow: none;
}

.user_option {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.user_option a {
  color: #ffffff;
  margin: 10px 30px;
}

.custom_nav-container .nav_search-btn {
  background-image: url(../images/search-icon.png);
  background-size: 22px;
  background-repeat: no-repeat;
  background-position-y: 7px;
  width: 35px;
  height: 35px;
  padding: 0;
  border: none;
}

.navbar-brand {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  position: relative;
}

.navbar-brand span {
  font-size: 22px;
  text-transform: uppercase;
  font-weight: bold;
  color: #ffffff;
  position: relative;
  z-index: 3;
}

.custom_nav-container {
  z-index: 99999;
  padding: 15px 0;
}

.custom_nav-container .navbar-toggler {
  outline: none;
}

.custom_nav-container .navbar-toggler .navbar-toggler-icon {
  background-image: url(../images/menu.png);
  background-size: 55px;
}

/*end header section*/
.slider_section {
  -webkit-box-flex: 1;
      -ms-flex: 1;
          flex: 1;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  color: #ffffff;
}

.slider_section #carouselExampleIndicators {
  width: 100%;
}

.slider_section .row {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.slider_section .box {
  margin: 125px 0;
}

.slider_section .detail-box {
  text-align: center;
}

.slider_section .detail-box h1,
.slider_section .detail-box h2,
.slider_section .detail-box h3 {
  text-transform: uppercase;
  font-weight: bold;
}

.slider_section .detail-box h2 {
  font-size: 2.5rem;
}

.slider_section .detail-box h1 {
  font-size: 3.5rem;
  font-weight: bold;
  letter-spacing: .5rem;
}

.slider_section .detail-box p {
  margin-top: 25px;
}

.slider_section .detail-box a {
  display: inline-block;
  padding: 8px 35px;
  background-color: transparent;
  border: 1.5px solid #ffffff;
  color: #ffffff;
  border-radius: 0px;
  -webkit-transition: -webkit-transform 0.3s;
  transition: -webkit-transform 0.3s;
  transition: transform 0.3s;
  transition: transform 0.3s, -webkit-transform 0.3s;
  text-transform: uppercase;
  margin-top: 35px;
}

.slider_section .detail-box a:hover {
  background-color: #ffffff;
  color: #000000;
}

.slider_section #carouselExampleIndicators .carousel-indicators {
  position: unset;
  margin: 0;
  margin-top: 45px;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.slider_section #carouselExampleIndicators .carousel-indicators li {
  width: 14px;
  height: 14px;
  background-color: transparent;
  border: 2px solid #ffffff;
  border-radius: 100%;
  opacity: 1;
}

.slider_section #carouselExampleIndicators .carousel-indicators li.active {
  border: 4px solid #ffffff;
}

.us_section {
  background-image: url(../images/us-bg.jpg);
  background-size: cover;
  background-attachment: fixed;
  color: #ffffff;
}

.us_section .us_container {
  padding-top: 25px;
}

.us_section .us_container .box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  text-align: center;
  margin: 25px 10px 0 10px;
}

.us_section .us_container .box .img-box {
  height: 100px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

.us_section .us_container .box .img-box img {
  max-width: 100%;
}

.us_section .us_container .box .detail-box h5 {
  font-weight: bold;
}

.heathy_section {
  background-image: url(../images/healthy-bg.jpg);
  background-size: cover;
  background-attachment: fixed;
  color: #ffffff;
  text-align: center;
}

.heathy_section h2 {
  font-weight: bold;
}

.heathy_section p {
  margin-top: 35px;
}

.heathy_section .btn-box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  margin-top: 45px;
}

.heathy_section .btn-box a {
  display: inline-block;
  padding: 8px 35px;
  background-color: transparent;
  border: 1.5px solid #ffffff;
  color: #ffffff;
  border-radius: 0;
  -webkit-transition: -webkit-transform 0.3s;
  transition: -webkit-transform 0.3s;
  transition: transform 0.3s;
  transition: transform 0.3s, -webkit-transform 0.3s;
  text-transform: uppercase;
}

.heathy_section .btn-box a:hover {
  background-color: #ffffff;
  color: #000000;
}

.trainer_section {
  background-image: url(../images/trainer-bg.jpg);
  background-size: cover;
  background-attachment: fixed;
  color: #ffffff;
}

.trainer_section .box {
  margin-top: 55px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  text-align: center;
}

.trainer_section .box .name h5 {
  font-weight: bold;
  margin-bottom: 15px;
}

.trainer_section .box .img-box {
  border-radius: 15px;
  overflow: hidden;
}

.trainer_section .box .img-box img {
  width: 100%;
}

.trainer_section .box .social_box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  width: 225px;
  padding: 12px 45px;
  background-color: #ffffff;
  border-radius: 50px;
  margin-top: -25px;
}

.contact_section {
  position: relative;
  background-color: #27223f;
  color: #ffffff;
}

.contact_section .heading_container {
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: start;
}

.contact_section .heading_container h2::before {
  text-align: left;
  left: 0;
  -webkit-transform: none;
          transform: none;
}

.contact_section .row {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.contact_section .img-box img {
  width: 100%;
}

.contact_section .form_container {
  padding: 45px 0 45px 15px;
}

.contact_section input {
  width: 100%;
  border: none;
  background-color: #ffffff;
  outline: none;
  color: #000000;
  margin-top: 25px;
  padding: 12px;
}

.contact_section input::-webkit-input-placeholder {
  color: #2a2a2c;
}

.contact_section input:-ms-input-placeholder {
  color: #2a2a2c;
}

.contact_section input::-ms-input-placeholder {
  color: #2a2a2c;
}

.contact_section input::placeholder {
  color: #2a2a2c;
}

.contact_section input.message-box {
  padding: 45px 12px;
}

.contact_section button {
  padding: 10px 65px;
  outline: none;
  border: none;
  color: #ffffff;
  background: #ff2953;
  margin: 45px 0 0 auto;
  text-transform: uppercase;
}

.info_section {
  background-color: #252233;
}

.info_items {
  width: 70%;
  margin: 0 auto;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
}

.info_items .item {
  width: 200px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  text-align: center;
}

.info_items .item .img-box {
  width: 80px;
  height: 80px;
  border-radius: 100%;
  background-repeat: no-repeat;
  background-position: center;
}

.info_items .item .detail-box {
  margin-top: 5px;
  color: #fff;
}

.info_items {
  position: relative;
}

.info_items a {
  position: relative;
}

.info_items .item .img-box.box-1 {
  background-image: url(../images/location-white.png);
}

.info_items .item .img-box.box-2 {
  background-image: url(../images/telephone-white.png);
}

.info_items .item .img-box.box-3 {
  background-image: url(../images/envelope-white.png);
}

/* footer section*/
.footer_section {
  background-color: #fbfdfd;
  padding: 20px;
  font-weight: 500;
}

.footer_section p {
  color: #292929;
  margin: 0;
  text-align: center;
}

.footer_section a {
  color: #292929;
}

/* end footer section*/
/*# sourceMappingURL=style.css.map *
