<template>
  <div>
    <div class="Box-container py-5">
      <div>
        <div class="row">
          <div class="col-8">
            <div class="text-g pb-3">SEND A MESSAGE</div>
            <h1 class="pb-5">
              <span>Get in</span><span class="pad-5 text-g">Touch</span>
            </h1>
            <p>Lorem ipsum dolor, sit ametvelit sint qui quas</p>

            <div>
              <div class="inpt-box my-3">
                <input
                  class="b-none form-control py-3 my-2 w-half bord-10 bg-grey"
                  type="text"
                  placeholder="Name"
                />
                <input
                  class="b-none form-control py-3 my-2 w-half bord-10 bg-grey"
                  type="email"
                  placeholder="Email"
                />
                <input
                  class="b-none form-control py-3 my-2 w-half bord-10 bg-grey"
                  type="number"
                  placeholder="Phone"
                />

                <select class="bg-grey b-none py-3 my-2 w-half  form-control w-half">
                  <option selected>more info ↷ </option>
                  <option value="1">One</option>
                  <option value="2">Two</option>
                  <option value="3">Three</option>
                </select>

                <input class="bg-grey b-none w_full" type="text" placeholder="message" style="height: 150px" />

              </div>

              <button class="btn my-2 my-3 btn-green">SEND</button>
            </div>
          </div>

          <div class="col-4 align-items-start">
              <h5>Example inc.</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
            <div class="py-2">icon +(305) 1234-5679</div>
            <div class="py-2">icon hello@example.com</div>
            <div class="py-2">icon Main Avenue, 987</div>
            <button class="btn btn-green-tex my-1">SEE ALL</button>

          </div>

        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "MainSendMessage",
};
</script>