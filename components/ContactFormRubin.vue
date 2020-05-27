<template>
  <form>
    <!-- Name -->
    <div class="field">
      <label class="label is-medium">First Name</label>
      <div class="control has-icons-left">
        <input class="input is-medium" type="email" placeholder="John" />
        <span class="icon is-small is-left">
          <font-awesome-icon icon="user" />
        </span>
      </div>
    </div>
        <div class="field">
      <label class="label is-medium">Last Name</label>
      <div class="control has-icons-left">
        <input class="input is-medium" type="email" placeholder="Smith" />
        <span class="icon is-small is-left">
          <font-awesome-icon icon="user" />
        </span>
      </div>
    </div>

    <!-- Email -->
    <div class="field">
      <label class="label is-medium">Email</label>
      <div class="control has-icons-left">
        <input
          class="input is-medium"
          type="email"
          placeholder="you@email.com"
        />
        <span class="icon is-small is-left">
          <font-awesome-icon icon="envelope" />
        </span>
      </div>
    </div>
        <!-- Email -->
    <div class="field">
      <label class="label is-medium">Phone</label>
      <div class="control has-icons-left">
        <input
          class="input is-medium"
          type="phone"
          placeholder="314.290.3400"
        />
        <span class="icon is-small is-left">
          <font-awesome-icon icon="phone" />
        </span>
      </div>
    </div>
    <!-- Subject -->
    <div class="field">
      <label class="label is-medium">Question</label>
      <div class="control has-icons-left">
        <input
          class="input is-medium"
          type="email"
          placeholder="Brief Summary"
        />
        <span class="icon is-small is-left">
          <font-awesome-icon icon="briefcase" />
        </span>
      </div>
    </div>
    <!-- Message -->
    <div class="field">
      <label class="label is-medium">Message</label>
      <div class="control">
        <textarea
          class="textarea"
          placeholder="Detailed description of your comment, request, etc"
          rows="8"
        ></textarea>
      </div>
    </div>
    <div class="control">
      <button class="button is-primary">
        Contact Us
      </button>
    </div>
  </form>
</template>
