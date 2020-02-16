# 
body {
  position: relative;
  margin: 0;
  min-width: 1408px;
  font-family: "Montserrat", "Helvetica", "Arial", sans-serif;
  font-size: 16px;
  line-height: 32px;
  color: #f2f2f2;
  background-color: #141530;
  background-image: url("img/pattern-lines-hero.svg");
  background-position: center;
}

.container {
  max-width: 1408px;
  margin: 0 auto;
  padding: 0 16px;
}

.page-header {
  margin: 0;
  padding: 40px 0;
}

.page-header a,
.page-footer a {
  position: relative;
  margin-right: 64px;
  padding-bottom: 10px;
  padding-top: 9px;
  font-weight: 500;
  text-decoration: none;
  background-repeat: no-repeat;
  background-position: left;
  color: inherit;
}

.page-header a:focus,
.page-header a:hover,
.page-footer a:focus,
.page-footer a:hover {
  color: #f9dd79;
}

.page-header a::after,
.page-footer a::after {
  position: absolute;
  content: "";
  bottom: 0;
  left: 0;
  width: 0;
  height: 2px;
  background-color: #f9dd79;
  transition: width 200ms;
}

.page-header a:hover::after,
.page-footer a:hover::after {
  width: 100%;
}

.header-email,
.footer-email {
  padding-left: 28px;
  background-image: url("img/icon-email.svg");
}

.header-email:focus,
.header-email:hover,
.footer-email:focus,
.footer-email:hover {
  background-image: url("img/icon-email-alt.svg");
}

.header-phone,
.footer-phone {
  padding-left: 21px;
  background-image: url("img/icon-phone.svg");
}

.header-phone:focus,
.header-phone:hover,
.footer-phone:focus,
.footer-phone:hover {
  background-image: url("img/icon-phone-alt.svg");
}

.page-header a:active,
.page-footer a:active {
  opacity: 0.5;
}

.hero-image {
  position: relative;
  padding-top: 200px;
  height: 798px;
  background-image: url("img/bg-html.png");
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: 48px;
}

.hero-image .container {
  display: flex;
  flex-direction: column;
}

.hero-image::before {
  position: absolute;
  content: "";
  top: 24px;
  left: calc(50vw - 32px);
  width: 800px;
  height: 800px;
  background-image: url("img/hero-image.svg");
  background-repeat: no-repeat;
}

.hero-image::after {
  position: absolute;
  content: "";
  height: 200px;
  width: 100%;
  bottom: 0;
  background-color: #0b0c23;
  background-image: url("img/bg-tags.svg");
  background-position: center;
  background-repeat: no-repeat;
  border-top: 2px solid #5053a8;
}

.heading {
  z-index: 1;
  order: 2;
  margin: 0 0 0 -10px;
  width: 815px;
  font-size: 96px;
  line-height: 112px;
  font-weight: 500;
}

.hero-image p {
  z-index: 1;
  order: 1;
  margin: 0;
  padding: 32px 0;
  padding-bottom: 16px;
  font-size: 32px;
  line-height: 48px;
  color: #f9dd79;
}

.intro,
.portfolio {
  background-color: #141530;
  background-image: url("img/pattern-lines.svg");
  background-repeat: repeat-y;
  background-position-x: center;
}

.intro {
  padding-top: 160px;
  padding-bottom: 120px;
  min-height: 828px;
}

.subheading {
  margin: 0 0 100px;
  text-align: center;
  font-size: 72px;
  line-height: 88px;
  font-weight: 500;
  color: #f9dd79;
}

.intro .container {
  position: relative;
}

.user-image {
  position: absolute;
  margin: 0;
}

.user-image img {
  width: 640px;
  height: 640px;
  object-fit: cover;
}

.intro .container div {
  margin-left: 720px;
  margin-bottom: 56px;
}

.intro h3,
.portfolio h3 {
  margin: 0 0 16px;
  font-size: 32px;
  line-height: 40px;
  font-weight: 500;
}

.intro p {
  margin: 0;
  z-index: 2;
}

.skills {
  margin-bottom: 0;
}

.skills h3 {
  margin-bottom: 40px;
}

.skills-list {
  margin: 0;
  padding: 0;
}

.skills-list dt {
  margin: 0 0 8px;
  padding-left: 46px;
  height: 36px;
  font-size: 24px;
  letter-spacing: 1px;
  background-repeat: no-repeat;
  background-position: left;
}

.skill-html {
  background-image: url("img/icon-html.svg");
}

.skill-css {
  background-image: url("img/icon-css.svg");
}

.level {
  margin: 0 0 40px;
  height: 24px;
  text-align: right;
  background-color: #0b0c23;
  box-shadow: inset 0 0 12px #070716;
  border-radius: 12px;
  overflow: hidden;
}

.skills .level div {
  margin: 0;
  height: 24px;
  letter-spacing: 1px;
  line-height: 26px;
  background-color: #5053a8;
  background-image: url("img/progress-pattern.svg");
}

.portfolio {
  margin: 0;
  padding-bottom: 160px;
}

.projects {
  margin: 0;
  padding: 0;
  list-style: none;
}

.projects li {
  position: relative;
  min-height: 256px;
  margin: 0 0 100px;
  padding-left: 528px;
}

.project-image {
  position: absolute;
  top: 0;
  left: 0;
  margin: 0;
}

.project-image img {
  width: 448px;
  height: 256px;
  object-fit: cover;
}

.projects p {
  margin: 0 0 32px;
}

.button {
  margin: 0;
  padding: 8px 24px;
  display: inline-block;
  vertical-align: baseline;
  font-size: 14px;
  font-weight: 500;
  letter-spacing: 1px;
  text-decoration: none;
  text-transform: uppercase;
  color: #0b0c23;
  background-color: #f9dd79;
  box-shadow: 0 4px 16px rgba(249, 221, 121, 0.4);
  border-radius: 24px;
  transition: background-color 100ms, box-shadow 100ms;
}

.button:focus,
.button:hover {
  background-color: #f9e7a8;
  box-shadow: 0 4px 32px rgba(249, 221, 121, 0.6);
}

.button:active {
  background-color: #b69e4b;
  box-shadow: none;
}

.page-footer {
  padding: 40px 0;
  background-color: #212349;
} 
