<style>
  #submit {
    border: none;
  }

  #submit:focus {
    border: none;
    outline: none;
  }

  form {
      width: 70%;
  }

  
</style>

<section class="seventh">
  <div class="text-container" />
  <div class="row">
    <div class="col-lg-6 col-md-12 colg-sm-12">
      <h1 class="title">Consult</h1>
      <p class="crypto_details">
        We offer a free consultation with our expert, where you get answers to
        your app development question and can discuss features of your project.
      </p>
    </div>
    <div class="col-lg-6 col-md-12 col-sm-12">
      <form>
        <div class="adjustment">
          <div class="form-group">
            <i class="fas fa-user" />
            <input type="text" class="form-control" placeholder="Name" />
          </div>
          <hr />
          <div class="form-group">
            <i class="fas fa-phone" />
            <input type="text" class="form-control" placeholder="Phone" />
          </div>
          <hr />
          <div class="form-group">
            <i class="fas fa-at" />
            <input
              type="email"
              class="form-control"
              id="exampleFormControlInput1"
              placeholder="name@example.com" />
          </div>
          <hr />

          <button class="float-right" id="submit">
            Submit<i class="fas fa-arrow-right" />
          </button>
        </div>
      </form>
    </div>
  </div>
</section>
