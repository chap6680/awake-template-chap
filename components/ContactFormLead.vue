<template>
<form action="https://webto.salesforce.com/servlet/servlet.WebToCase?encoding=UTF-8" method="POST">
<input type=hidden name="orgid" value="00D5w000007AjKI">
<input type=hidden name="retURL" value="https://www.rubinbrown.com/article/8334/COVID-19-Updates-to-the-PPP-Loan-Frequently-Asked-Questions.aspx?articlegroup=1059">

    <!-- Name -->
    <div class="field">
      <label class="label is-medium">First Name</label>
      <div class="control has-icons-left">
        <input class="input is-medium" id="00N5w00000QFkia" maxlength="75" name="00N5w00000QFkia" type = "text" placeholder="John" />
        <span class="icon is-small is-left">
          <font-awesome-icon icon="user" />
        </span>
      </div>
    </div>
        <div class="field">
      <label class="label is-medium">Last Name</label>
      <div class="control has-icons-left">
        <input class="input is-medium" id="00N5w00000QFkif" maxlength="255" name="00N5w00000QFkif"  placeholder="Smith" />
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
          name="email"
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
          id="00N5w00000QFkiV" maxlength="255" name="00N5w00000QFkiV"
          class="input is-medium"
          type="text"
          placeholder="Question"
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
          name="description"
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
