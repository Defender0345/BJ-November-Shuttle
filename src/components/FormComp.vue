<script></script>

<template>
  <section id="contact" class="contact flex-columns">
    <div class="line"></div>
    <div class="row">
      <div class="column">
        <div class="column-1">
          <img src="../assets/Images/Businesscard-No-BG.png" alt="" />
        </div>
      </div>
      <div class="column">
        <div class="column-2 gradient">
          <h2>Contact Us</h2>
          <!-- Netlify Form -->
          <form name="contact" netlify method="POST" data-netlify="true" class="callback-form">
            <div class="form-control text-fields">
              <input
                type="hidden"
                name="subject"
                data-remove-prefix
                value="Dylan Portfolio Website Form Submission (%{submissionId})"
              />
              <input type="hidden" name="form-name" value="ask-question" />
              <!-- Honeypot field -->
              <div style="display: none">
                <label>
                  Don’t fill this out if you're human:
                  <input name="bot-field" />
                </label>
              </div>
              <!-- Name Field -->
              <input
                type="text"
                class="text-input name-input"
                placeholder="Name..."
                name="name"
                required
              />
              <!-- Subject Field -->
              <input
                type="text"
                class="text-input subject-input"
                placeholder="Subject..."
                name="subject"
              />
              <!-- Email Field -->
              <input
                type="email"
                class="text-input email-input"
                placeholder="Email Address..."
                name="email"
                required
              />
              <!-- Phone Area -->
              <input
                type="text"
                class="text-input phone-input"
                placeholder="Phone Number"
                name="phone"
              />
              <!-- Text Area -->
              <textarea
                class="text-input message-input"
                placeholder="Enter Message..."
                name="message"
                required
              ></textarea>
            </div>
            <button type="submit" class="btn">Submit</button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import '@/assets/_shared.scss';

.contact {
  img {
    width: 100%;
    height: 100%;
    object-fit: scale-down;
  }
}

.gradient {
  background-image: linear-gradient(90deg, #43bbfe 10%, #324488 100%);
}
.callback-form {
  width: 100%;
  padding: 20px 0;
  .form-control {
    margin-bottom: 15px;
    label {
      display: block;
      margin-bottom: 5px;
    }
    input {
      width: 100%;
      padding: 4px;
      margin: 5px;
      height: 40px;
      border: #f5f5f5 1px solid;
      &:focus {
        outline-color: #43bbfe;
      }
    }
    textarea {
      width: 100%;
      height: 70px;
      padding: 4px;
      margin: 5px;
      border: #f5f5f5 1px solid;
      &:focus {
        outline-color: #43bbfe;
      }
    }
    .btn {
      padding: 12px 0;
      margin-top: 20px;
      &:hover {
        background-color: #43bbfe;
      }
    }
  }
}

@media (max-width: 768px) {
  .contact {
    .row {
      flex-direction: column !important;
    }
  }
}
</style>
