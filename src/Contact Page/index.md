---
layout: base.njk
title: Contact
---
<style>
  @font-face {
    font-family: 'Nunito';
    font-weight: 400;
    src: url('assets/fonts/nunito-variablefont_wght-webfont.woff2') format('woff2'),
        url('assets/fonts/nunito-variablefont_wght-webfont.woff') format('woff');

  }
   body {
      font-family: "Nunito", sans-serif;
      background-color:#7da0b6;
      margin: ;
      padding: 0;
      display: flex;
      flex-direction: column;
   }
  form {
    background-color: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 4px 100px rgba(0, 0, 0, 0.1);
    padding: 2em;
    max-width: 500px;
    margin: 0 auto;
    font-family: "Nunito", serif;
    color: #333;
    padding: 1.3rem;

    

  }
  h2 {
    font-family: "Nunito", sans-serif;
    font-size: 1.75rem;
    font-weight: 500;
    color: #000000;
    margin-bottom: 1.5em;
    text-align: center; 
    padding: 1rem;
  }

    h3 {
    font-family: "Nunito", sans-serif;
    font-size: 1.75rem;
    font-weight: 500;
    color: #000000;
    margin-bottom: 1.5em;
    text-align: center; 
     padding-top: 1.8rem;
  }
  
  input,
  textarea {
    font-family: inherit;
    font-size: 1rem;
    width: 100%;
    padding: 0.5em;
    margin-bottom: 1.5em;
    border: 1px solid black;
    border-radius: 1px;
    transition: border-color 0.3s ease;
  }

  label {
    font-weight: 600;
    margin-bottom: 0.5em;
    color: #00000;
  }

  textarea {
    height: 100px;
    resize: vertical;
  }

  button[type="submit"] {
    font-size: 1rem;
    padding: 1em;
    background-color: #005555;
    color: #ffff;
    width: 100%;
  }

  

  

 

  @media (max-width: 800px) {
    form {
      padding: 1em;
    }
  }
</style>

<h2>Adopt a Pet</h2>

<form name="contact" netlify>
  <p>
    <label for="name">Pet Name:</label>
    <input type="text" id="name" name="name" required>
  </p>
  <p>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
  </p>
 <p>
    <label for="number">Phone Number:</label>
    <input type="number" id="number" name="phone number" required>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

<h3> Volunteer for us </h3>

<form name="contact" netlify>
  <p>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
  </p>
  <p>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
  </p>
 <p>
    <label for="number">Phone Number:</label>
    <input type="number" id="number" name="phone number" required>
  </p>
  <p>
    <label for="message">Additonal Comments:</label>
    <textarea id="message" name="additional comments" required ></textarea>
  </p>
  <p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>