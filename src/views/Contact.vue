<template>
    <main role="main" class="inner cover text-light">
     <h1 class="display-3">Contact Us</h1>
        <div class="container pt-5">
          <div class="row">
            <div class="col-md-4 mb-3 mb-md-0">
              <div class="card">
                <div class="card-body">
                  <h4 class="card-title text-center">
                    <span class="text-center">
                      <i class="fas fa-map-marked-alt"></i> </span
                    ><br />
                    Address
                  </h4>
                  <hr class="hr-contact" />
                  <p class="card-text text-center">
                    123 Main St. Aplace, VA 12345
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md-4 mb-3 mb-md-0">
              <div class="card">
                <div class="card-body">
                  <h4 class="card-title text-center">
                    <span class="text-center">
                      <i class="fas fa-envelope"></i> </span
                    ><br />
                    Email
                  </h4>
                  <hr class="hr-contact" />
                  <p class="card-text text-center">
                    esuna-noodles@email.com
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md-4 mb-3 mb-md-0">
              <div class="card">
                <div class="card-body">
                  <h4 class="card-title text-center">
                    <span class="text-center">
                      <i class="fas fa-mobile-alt"></i> </span
                    ><br />
                    Phone
                  </h4>
                  <hr class="hr-contact" />
                  <p class="card-text text-center">
                    (123) 456-7890
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
    </main>
</template>

<script>
export default {};
</script>

<style scoped>
.card {
  background-color: transparent;
  border: 1px solid #fff;
}

.hr-contact {
  border: 2px solid #fff;
  width: 50%;
}
</style>
