<template>
  <div class="header_section header_bg">
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#"
          ><img src="images/logo.png"
        />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="coffee">Coffees</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/blog">Blog</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="/contact">Contact</a>
            </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <div class="login_bt">
              <ul>
                <li>
                  <a href="#"
                    ><span class="user_icon"
                      ><i class="fa fa-user" aria-hidden="true"></i></span
                    >Login</a
                  >
                </li>
                <li>
                  <a href="#"
                    ><i class="fa fa-search" aria-hidden="true"></i
                  ></a>
                </li>
              </ul>
            </div>
          </form>
        </div>
      </nav>
    </div>
  </div>
  <!-- header section end -->
  <!-- contact section start -->
  <div class="contact_section layout_padding">
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <h1 class="contact_taital">Get In Touch</h1>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="contact_section_2">
        <div class="row">
          <div class="col-md-12">
            <div class="mail_section_1">
              <input
                type="text"
                class="mail_text"
                placeholder="Your Name"
                name="Your Name"
              />
              <input
                type="text"
                class="mail_text"
                placeholder="Your Email"
                name="Your Email"
              />
              <input
                type="text"
                class="mail_text"
                placeholder="Your Phone"
                name="Your Phone"
              />
              <textarea
                class="massage-bt"
                placeholder="Massage"
                rows="5"
                id="comment"
                name="Massage"
              ></textarea>
              <div class="send_bt"><a href="#">Send</a></div>
            </div>
          </div>
          <div class="map_main">
            <div class="map-responsive">
              <iframe
                src="https://www.google.com/maps/embed/v1/place?key=AIzaSyA0s1a7phLN0iaD6-UE7m4qP-z21pH0eSc&amp;q=Eiffel+Tower+Paris+France"
                width="250"
                height="500"
                frameborder="0"
                style="border: 0; width: 100%"
                allowfullscreen=""
              ></iframe>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- contact section end -->
  <!-- footer section start -->
  <div class="footer_section layout_padding">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="footer_social_icon">
            <ul>
              <li>
                <a href="#"
                  ><i class="fa fa-facebook" aria-hidden="true"></i
                ></a>
              </li>
              <li>
                <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
              </li>
              <li>
                <a href="#"
                  ><i class="fa fa-linkedin" aria-hidden="true"></i
                ></a>
              </li>
              <li>
                <a href="#"
                  ><i class="fa fa-instagram" aria-hidden="true"></i
                ></a>
              </li>
            </ul>
          </div>
          <div class="location_text">
            <ul>
              <li>
                <a href="#">
                  <i class="fa fa-phone" aria-hidden="true"></i
                  ><span class="padding_left_10">0789326245</span>
                </a>
              </li>
              <li>
                <a href="#">
                  <i class="fa fa-envelope" aria-hidden="true"></i
                  ><span class="padding_left_10">demo@gmail.com</span>
                </a>
              </li>
            </ul>
          </div>
          <div class="form-group">
            <textarea
              class="update_mail"
              placeholder="Your Email"
              rows="5"
              id="comment"
              name="Your Email"
            ></textarea>
            <div class="subscribe_bt">
              <a href="#"
                ><i class="fa fa-arrow-right" aria-hidden="true"></i
              ></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- footer section end -->
  <!-- copyright section start -->
  <div class="copyright_section">
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <p class="copyright_text">
            2024 All Rights Reserved. Design by
            <a href="#">Heritier Ganza Tamba</a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
