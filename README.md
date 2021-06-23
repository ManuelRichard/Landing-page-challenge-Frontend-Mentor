<h1>Lading page Frontend Mentor challenge</h1>
<p>
  This README.md file explains the content of some folders and files, in this
  way you will see the structure that I have followed.
</p>
<section>
  <h2>Folders</h2>
  <ul>
    <li>
      <h3>components</h3>
      <p>
        in this folder are the code blocks that can become repetitive on a page,
        as in this case the form was. In the hypothetical case that the project grows, here I also added the testimonials
      </p>
    </li>
    <li>
      <h3>Base</h3>
      <p>
        In this folder there would be rules that affect several elements at the
        same time, that is, global rules. It could also be code formatters like
        normalize
      </p>
    </li>
  </ul>
</section>
<section>
  <h2>Files</h2>
  <ul>
    <li>
      <h3>Funtion</h3>
      <p>
        In the <code>_functions.scss</code> file there is a function called
        "Title", whose purpose besides gathering all the titles of the page in a
        single variable, is to save me having to write
        <code> font-size: variables.$font-title + (font-size) </code> for each
        title. The sum parameter it receives is simply the size we'll give the
        title, which doesn't actually add up to anything, unless you add a value
        greater than 0 to the <code>$font-title</code> variable.
      </p>
    </li>
    <li>
      <h3>Variable</h3>
      <p>
        In the <code>_variables.scss</code> file, the variable
        <code>--margin-global</code> is the value of the margin of the sides of
        the page, the variable is added to separate elements, i.e. to the
        <code>header</code>, <code>main</code>, etc.. the reason is that that
        was the most optimal way that I found to be able to place the background
        the of page, since the background occupies the whole page I can't give
        it --margin-global to the body.
      </p>
    </li>
  </ul>
</section>
<article>
  <h2>form validation message with CSS</h2>
  <p>
    In the file <code> _form.scss </code> from line 29 to line 65, I wrote the
    form valid ation message for the <code> header </code> and the
    <code> footer </code>, in which it basically says: When the input is in the
    <code> focus </code> state, go to the state <code> valid </code> or
    <code> invalid </code>, then go to the next direct sibling and apply the
    corresponding classes that are in the <code> :: before </code> or
    <code> pseudo-element :: after </code> from the same sibling.
  </p>
</article>
