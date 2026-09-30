<template>
  <section id="contact">
    <div class="container section-card">
      <div class="contact-wrapper">
        <div class="contact-left">
          <h2>Let's Get in Touch</h2>
          <div class="accent-line"></div>
          <p>
            I am always open to new opportunities and collaborations. Feel free
            to reach out.
          </p>
          <div class="contact-details">
            <p>
              <span class="contact-label">Email:</span> knonhlanhla585@gmail.com
            </p>
            <p>
              <span class="contact-label">Location:</span> Cape Town, South
              Africa
            </p>
          </div>
          <div class="contact-links">
            <a
              href="https://linkedin.com/in/nonhlanhla-kunene-8416ba369"
              target="_blank"
              rel="noopener"
            >
              <i class="fa-brands fa-linkedin"></i> LinkedIn
            </a>
            <a
              href="https://github.com/nonhlanhlakunene"
              target="_blank"
              rel="noopener"
            >
              <i class="fa-brands fa-github"></i> GitHub
            </a>
          </div>
        </div>
        <div class="contact-right">
          <form
            action="https://api.web3forms.com/submit"
            method="POST"
            class="contact-form"
          >
            <input
              type="hidden"
              name="access_key"
              value="4709d36b-cbc5-4448-8141-407cb7407fed"
            />
            <div class="form-group">
              <label for="name">Name</label>
              <input
                type="text"
                name="name"
                id="name"
                placeholder="Your full name"
                required
              />
            </div>
            <div class="form-group">
              <label for="email">Email</label>
              <input
                type="email"
                name="email"
                id="email"
                placeholder="your@email.com"
                required
              />
            </div>
            <div class="form-group">
              <label for="subject">Subject</label>
              <input
                type="text"
                name="subject"
                id="subject"
                placeholder="What is this about?"
              />
            </div>
            <div class="form-group">
              <label for="message">Message</label>
              <textarea
                name="message"
                id="message"
                rows="5"
                placeholder="Write your message here..."
                required
              ></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
