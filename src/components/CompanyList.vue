<template>
  <div class="container">
    <div class="row">
      <div class="col-md-4 col-sm-6 col-xs-12">
        <b-card
          title="Place 1"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-4"
        >
          <b-card-text>welcome to summer city</b-card-text>
          <b-button v-b-modal.modal-1 href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </div>
      <div class="col-md-4 col-sm-6 col-xs-12">
        <b-card
          title="Place 2"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-4"
        >
          <b-card-text>welcome to winter-land city</b-card-text>
          <b-button v-b-modal.modal-1 href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </div>
      <div class="col-4">
        <b-card
          title="Place 3"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-4"
        >
          <b-card-text>welcome to riverlan city</b-card-text>
          <b-button v-b-modal.modal-1 href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </div>
    </div>
    <Modal data title/>
  </div>
</template>

<script>
import Modal from "./Modal";

export default {
  name: " CompanyList",
  components: {
    Modal
  }
};
</script>