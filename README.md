<h1>Lading page Frontend Mentor challenge</h1>
<p>
  this README file will be dedicated to explain a
  bit of how I have organized the SASS code and some functions of the same.
</p>
<section>
  <h2>SCSS code structure</h2>
  <ul>
    <li>
      <h3>components</h3>
      <p>
        In this folder you'll find all the files that contain the
        functionalities that SASS allows us to do, such as: functions, mixins,
        extends etc.
      </p>
      <ul>
        <li>
          <h4>Function</h4>
          <p>
            In the <code>_functions.scss</code> file there is a function called
            "Title", whose purpose besides gathering all the titles of the page
            in a single variable, is to save me having to write
            <code> font-size: variables.$font-title + (font-size) </code> for
            each title. The sum parameter it receives is simply the size we'll
            give the title, which doesn't actually add up to anything, unless
            you add a value greater than 0 to the
            <code>$font-title</code> variable.
          </p>
          <h4>Variable</h4>
          <p>
            In the <code>_variables.scss</code> file, the variable
            <code>--margin-global</code> is the value of the margin of the sides
            of the page, the variable is added to separate elements, i.e. to the
            <code>header</code>, <code>main</code>, etc.. the reason is that
            that was the most optimal way that I found to be able to place the
            background the of page, since the background occupies the whole page
            I can't give it --margin-global to the body.
          </p>
        </li>
      </ul>
    </li>
    <li>
      <h3>frequent-block</h3>
      <p>
          In this folder I added sections of code that can be repeated on a page, as in this case it was the form.
      </p>
    </li>
  </ul>
</section>
<section>
  <h2>Little tip</h2>
  <ul>
    <li>
      <h3>form validation message with CSS</h3>
      <p>
        In the file <code> _form.scss </code> from line 29 to line 65, I wrote
        the form valid ation message for the <code> header </code> and the
        <code> footer </code>, in which it basically says: When the input is in
        the <code> focus </code> state, go to the state <code> valid </code> or
        <code> invalid </code>, then go to the next direct sibling and apply the
        corresponding classes that are in the <code> :: before </code> or
        <code> pseudo-element :: after </code> from the same sibling.
      </p>
    </li>
  </ul>
</section>
