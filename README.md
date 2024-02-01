# CatWebsite_FreeCodeCamp
HTML tags give a webpage its structure. You can use HTML tags to add photos, buttons, and other elements to your webpage.  In this course, you'll learn the most common HTML tags by building your own cat photo app.

<!DOCTYPE html>
 <html lang="en">

   <head>
      <title>CatPhotoApp</title>
      <meta charset='UTF-8'>
   </head>

   <body>
      <main>
        <h1>CatPhotoApp</h1>

        <section>
         <h2>Cat Photos</h2>
          <!--TODO: Add link to cat photos-->
          <p>See more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a> in our gallery</p>
          <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back"></a>
       </section>

       <section>
         <h2>Cat Lists</h2>
         <h3>Things cats love:</h3>

         <ul>
            <li>cat nip</li>
            <li>laser pointers</li>
           <li>lasagna</li>
         </ul>

         <figure>
           <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
           <figcaption>Cats <em>love</em> lasagna</figcaption>
         </figure>

          <h3>Top 3 things cats hate:</h3>

          <ol>
            <li>flea treatment</li>
            <li>thunder</li>
            <li>other cats</li>
          </ol>

         <figure>
           <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a filed">
           <figcaption>Cats <strong>hate</strong> other cats</figcaption>
         </figure>

        </section>

       <section>
          <h2>Cat Form</h2>
          <form action="https://freecatphotoapp.com/submit-cat-photo"><input type="text" name="catphotourl" placeholder="cat photo URL" required>
        
           <fieldset>
             <legend>Is your cat an indoor or outdoor cat?</legend>
             <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor </label>
             <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor </label>
             <button type="submit">Submit</button>
           </fieldset>

           <fieldset>
              <legend>What's your cat's personality?</legend>
              <input id="loving" type="checkbox" name="personality" value="loving" checked><label>Loving</label>
              <input id="lazy" type="checkbox" name="personality" value="lazy"><label>Lazy</label>
              <input id="energetic" type="checkbox" name="personality" value="energetic"><label>Energetic</label>
            </fieldset>
          </form>

        </section>

      </main>
             <footer>
               <p>No Copyright -<a href="https://www.freecodecamp.org">freeCodeCamp.org</a></p>
           </footer>
     </body>
</html>
