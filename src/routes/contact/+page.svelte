<script>
  import MdEmail from 'svelte-icons/md/MdEmail.svelte';
</script>

<div class="grid mx-auto grid-cols-1 md:grid-cols-2 gap-5 p-4">
  <!-- Contact Form Card -->
  <div class="card card-hover overflow-hidden shadow-lg rounded-lg">
    <header class="p-4 bg-primary rounded-t-lg">
      <h3 class="text-lg font-bold">Contact Me</h3>
    </header>
    <div class="p-4 space-y-4">
      <form class="space-y-4">
        <div>
          <label for="name" class="text-md font-bold">Name</label>
          <input
            type="text"
            id="name"
            name="name"
            class="input"
            placeholder="Enter your name"
          />
        </div>
        <div>
          <label for="email" class="text-md font-bold">Email</label>
          <input
            type="email"
            id="email"
            name="email"
            class="input"
            placeholder="Enter your email"
          />
        </div>
        <div>
          <label for="subject" class="text-md font-bold">Subject</label>
          <input
            type="text"
            id="subject"
            name="subject"
            class="input"
            placeholder="Enter subject"
          />
        </div>
        <div>
          <label for="message" class="text-md font-bold">Message</label>
          <textarea
            id="message"
            name="message"
            rows="6"
            class="textarea"
            placeholder="Type your message"></textarea>
        </div>
      </form>
    </div>
    <footer class="p-4 text-center">
      <button type="button" class="btn variant-filled">
	    <span>Send Message</span>
      </button>
    </footer>
  </div>

  <!-- Contact Details Card -->
  <div class="card card-hover overflow-hidden shadow-lg rounded-lg">
    <header class="p-4 bg-primary rounded-t-lg">
      <h3 class="text-lg font-bold">Contact Details</h3>
    </header>
    <div class="p-4 space-y-4">
      <div class="flex items-center space-x-2">
        <MdEmail class="h-6 w-6 text-primary" />
        <span>dylanpoljak@icloud.com</span>
      </div>
    </div>
  </div>
</div>
