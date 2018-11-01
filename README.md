<!DOCTYPE html>
<html>
  <head>

  </head>
      
  <body>
    <h1>My Form</h1>
    <form action="my-handling-form-page" method="POST">
      <div>
        <label for="name">Name:</label>
        <input type="text" id="name" name="user_name" placeholder="Your Full name">
      </div>
      <div>
        <label for="mail">E-mail:</label>
        <input type="email" id="Mail name" name="user_mail" placeholder="Your email address" required>
      </div>
      <div>
        <label dor="msg"> Message:</label>
        <textarea id="msg" name="user_message"></textarea>
       </div>
       <div>
          <input type="checkbox" value="Yes send me emails about your news and updates!">
       </div>
          <input type="sumbit" value="Sign up to the mailing list">
    </form>
  </body>
</html>