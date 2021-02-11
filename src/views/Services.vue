<template>
  <div class="container text-center">
    <br /><br /><br /><br />
    <h1>Pricing</h1>
    <br /><br />
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">Lowest Cost</div>
            <div class="card-body">
              <h5 class="card-title">Starter Deals</h5>
              <img
                src="data:image/jpeg;base64,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"
                alt="bronze"
                width="80%"
              />
              <p class="card-text">
                Build 1 to 3 page site <br />
                <strong style="font-size: 32px;">$165</strong>
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">Best Value Cost</div>
            <div class="card-body">
              <h5 class="card-title">Starter Deals</h5>
              <img
                src="https://301txf2j650kx3hvubmojefm-wpengine.netdna-ssl.com/wp-content/uploads/2018/01/BONS-platinum-package.jpg"
                alt="bronze"
                width="80%"
              />
              <p class="card-text">
                Build 1 to 5 page site <br />
                <strong style="font-size: 32px;">$245</strong>
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">Lowest Cost</div>
            <div class="card-body">
              <h5 class="card-title">Starter Deals</h5>
              <img
                src="https://th.bing.com/th/id/Rdba356c33aa6c011596a0b8333bf80be?rik=2DDsWrFPJMKQVQ&riu=http%3a%2f%2f1elemental.com%2fwp-content%2fuploads%2f2016%2f04%2fgold-package_.png&ehk=lPZud%2faqJ2jyvPwz%2fxqvCHeucaivToif4BhE2nd7lkA%3d&risl=&pid=ImgRaw"
                alt="bronze"
                width="87%"
              />
              <p class="card-text">
                Build 1 to 7 page site <br />
                <strong style="font-size: 32px;">$335</strong>
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <div class="jumbotron">
      <img
        src="https://cdn.pixabay.com/photo/2019/07/05/20/21/customer-review-4319316_1280.png"
        alt="customers"
        width="290px"
      />
      <h1>What Customers Say</h1>
      <br />
      <div class="container">
        <div class="row">
          <div class="col-md-3">
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star"></i>
            <br />
            <br />
            <img
              src="https://reiblaw.com/wp-content/uploads/2019/05/5-essential-tips-for-starting-your-own-business.jpg"
              alt="customer"
              class="img-fluid rounded"
              width="140px"
            /><br />
            <h5>Crystal Haymon</h5>
            <small>
              "Timely with his service and gave us exactly what we needed."
            </small>
          </div>
          <div class="col-md-3">
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star"></i>
            <br />
            <br />
            <img
              src="https://surveyanyplace.com/wp-content/uploads/Customer-Satisfaction-Survey-Questions-1.jpg"
              alt="customer"
              class="img-fluid rounded"
              width="175px"
            /><br />
            <h5>GodJotters</h5>
            <small>
              "He was an inspiration and nice to have on a temp project."
            </small>
          </div>
          <div class="col-md-3">
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star"></i>
            <br />
            <br />
            <img
              src="https://assets.entrepreneur.com/content/3x2/2000/20190219215328-GettyImages-763163459.jpeg?width=1000"
              alt="customer"
              class="img-fluid rounded"
              width="140px"
            /><br />
            <h5>Mike Sloan</h5>
            <small>
              "Mr. Brooks solved my website problems and went the extra mile."
            </small>
          </div>
          <div class="col-md-3">
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star"></i> <i class="fas icon fa-star"></i>
            <i class="fas icon fa-star-half-alt"></i>
            <br />
            <br />
            <img
              src="https://assets.entrepreneur.com/content/3x2/1300/20160803162356-smallbusinesslaptops.jpeg"
              alt="customer"
              class="img-fluid rounded"
              width="140px"
            /><br />
            <h5>Ms. Thompson</h5>
            <small>
              "He was very helpful and worked very fast to get my site up."
            </small>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <br />
  </div>
</template>

<style lang="scss" scoped>
.icon {
  font-size: 1.4em;
  color: goldenrod;
}
.round {
  border-radius: 50%;
}
</style>
