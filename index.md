<!DOCTYPE html>
<html>
  <head>
    <title>HTML</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/732/732212.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=BioRhyme:wght@200..800&display=swap" rel="stylesheet"> 
  </head>
  <body>
    <Header>
      <nav id="home">
        <a href="./HTML.html">HTML</a>
        <a href="./CSS.html">CSS</a>
        <a href="./Leisure.html">2nd Page</a>
      </nav>
    </Header>
    <img class="back" src="https://dcblog.b-cdn.net/wp-content/uploads/2021/02/html.jpg">
    <main>
      <div id="stik" class="er">
        <a href="https://w3schools.com/html" target="_blank"><h2>Elements: < ><br>Attributes: =</h2></a>
      </div>
     <br>
      <section class='list'>
        <ul>
          <h3>page formatting</h3>
          <li class="marg">Shows HTML version (!DOCTYPE html)</li>
          <li>HTML code identifier (html)</li>
          <li>Head contains metadata of page (head)</li>
          <li>Browser tab text (title) *put in head*</li>
          <li>Dispayable content (body)</li>
          <li>Header (header) *can contain nav*</li>
          <li>Navigaion links (nav)</li>
          <li>Main content (main)</li>
          <li>Footer (footer)</li>
        </ul>
        <ul>
          <h3>Text</h3>
          <li>Paragraph (p)</li>
          <li>Headings (H1-H6)</li>
          <li>Bullpoint lists (ul{li})</li>
          <li>Numbered lists (ol{li})</li>
        </ul>
        <ul class="wid">
          <h3>Styling</h3>
          <li><strong>Bold text (strong)</strong></li>
          <li><em>Italic text (em)</em></li>
          <li>Line accrose page (hr)</li>
          <li>Allign shade size & width (align=/noshade=/size=/width=) <span class="th">*Deprecated attributes*</span></li>
          <li>Line breaks (br)</li>
          <li>Inline container (span)</li>
        </ul>
        <ul>
          <h3>Links</h3>
          <li><a href="https://thehandbookcompany.com/prices">External links </a>(a/href="URL")</li>
          <li><a href="./CSS.html">Internal links</a> (a/href="./????.html")</li>
          <li><a href="https://thehandbookcompany.com"target="_blank">Open in new tab</a> (target="_blank")</li>
          <li><a href="#table">Hyperlinks</a> (href="#{id's target}")</li>
          <li>sdfhasjdfad</li>
        </ul>
        
        <ul>
          <h3>Media</h3>
          <li>image(img/src="URL"/alt="?")*Self closing*</li>
          <li>wrap anchor (a/href="URL") around an image to make it a link</li>
          <li>Videos (video/src="URL"/width=/height=/controls+Video not supported)</li>
          <li>Audio (audio/source/src=/controls) *source tag in self closing*</li>
          <li>Add controls to video/audio (controls) *attribute*</li>
          <li>Make the video play as soon as the page is loaded (autoplay) *attribute*</li>
          <li>Video plays on repeat (loop) *attribute*</li>
          <li>Embed any media on your site (embed) *self closing.<span class="th"> Deprecated tag*</span></li>
        </ul>
        <ul>
          <h3>Formatting/Semantics</h3>
          <li>Dividers (div) *can't be used alone*</li>
          <li>Section content (section) *can't be used alone*</li>
          <li>Articles (article) *can't be used alone*</li>
          <li>Sidenotes (aside) *can't be used alone*</li>
          <li>Image Sidenote (figure) *can't be used alone*</li>
          <li>Image sidenote description (figcaption) *place inside figure*</li>
          <li>Comments arn't visible (!-- --)</li>
          <!-- This a comment demonstration -->
          <li>Deprecated tag may not work in the latest versions of HTML</li>
          <li>Whitespace/Indentation won't change the output</li>
          <li>2 spaces is standard indentation</li>
        </ul>
      </section><br>
      <section>
        <table border="2">
          <tr>
            <th>Function</th>
            <th>Tag/s</th>
            <th>Attributes</th>
            <th>Notes</th>
          </tr>
          <tr>
            <td>Form</td>
            <td>form</td>
            <td>action=/method=</td>
            <td></td>
          </tr>
          <tr>
            <td>Label</td>
            <td>label</td>
            <td>for="{id}"</td>
            <td></td>
          </tr>
          <tr>
            <td>Input</td>
            <td>input</td>
            <td>type=/id=/name=(/value=/list=/required)</td>
            <td>self closing tag. name attribute is required</td>
          </tr>
          <tr>
            <td>Text field</td>
            <td>"</td>
            <td>type="text" (minlength=/maxlength=pattern=)</td>
            <td>Values' value will show in user's text field</td><!-- Once submitted the text field will be the value=*whetever the user typed* and is paired with the name attrib (i.e. name value=user input)-->
          </tr>
          <tr>
            <td>Text list</td>
            <td>" datalist</td>
            <td>id=</td>
            <td>List attribute required</td>
          </tr>
          <tr>
            <td>" options</td>
            <td>" " option</td>
            <td>Value=</td>
            <td>Value attribute will display text on screen</td>
          </tr>
          <tr>
            <td>Password field</td>
            <td>"</td>
            <td>type="password" (minlength=/maxlength=/pattern=)</td>
            <td>*name value*=*user password* when submitted</td>
          </tr>
          <tr>
            <td>Number field</td>
            <td>"</td>
            <td>type="number" (min=?/max=?/step=?/pattern=?)</td>
            <td>Step attribute adds arrows and skip rate</td>
          </tr>
          <tr>
            <td>Slider</td>
            <td>"</td>
            <td>type="range" (min=?/max=?/step=?)</td>
            <td>Step attribute determines smoothness</td>
          </tr>
          <tr>
            <td>Multiple choice</td>
            <td>"</td>
            <td>type="checkbox"</td>
            <td>Value attribute required. Group id attributes</td>
          </tr>
          <tr>
            <td>Single choice</td>
            <td>"</td>
            <td>type="radio"</td>
            <td>Value attribute is required. Group id attributes</td>
          </tr>
          <tr>
            <td>Submit form</td>
            <td>"</td>
            <td>type="submit"/value=</td>
            <td>Name not required. will display submit if no value</td>
          </tr>
          <tr>
            <td>Dropdown menu</td>
            <td>select</td>
            <td>id=/name=</td>
            <td></td>
          </tr>
          <tr>
            <td>" options</td>
            <td>" option</td>
            <td>value=</td>
            <td>Value attribute won't display text</td>
          </tr>
          <tr>
            <td>Extra text</td>
            <td>textarea</td>
            <td>id=/name=/rows=/cols=(minlength=/maxlength=)</td>
            <td></td>
          </tr>
        </table>
      </section>
        <br>
      <section class="ol">
        <ol>
          <li>action="?" determines where information is sent to</li>
          <li>method="?"attribute determines how the information is sent and processed</li>
          <li>name="?" specifies the name of an input element</li>
          <li>required attribute makes an input field mandatory</li>
          <li>pattern= determines which charachter combinations need to be met<br> [?-?]=determine which charachters are allowed,{?,?}=determine how man times a charachter is allowed, + determines if a charachter is allowed more than once</li>
        </ol>
      </section>
      </ul>
      <br>
      <section>
      <table border="2" id="table">
        <thead>
          <tr>
            <th></th>
            <th>Function</th>
            <th>Element tag/s</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th rowspan="5">Element</th>
            <td>Table</td>
            <td>table</td>
          </tr>
          <tr>
            <td>Table row</td>
            <td>tr</td>
          </tr>
          <tr>
            <td>Table header</td>
            <td>th</td>
          </tr>
          <tr>
            <td>Table data</td>
            <td>td</td>
          </tr>
          <tr>
            <td>Divide table into header/body/footer</td>
            <td>thead/tbody/tfoot</td>
          </tr>
          <tr>
            <th rowspan="4">Attributes</th>
            <td>Attribute headings for colums/rows</td>
            <td>scope=col/row</td>
          </tr>
          <tr>
            <td>Spanmultiple rows</td>
            <td>rowspan=?</td>
          </tr>
          <tr>
            <td>Span multiple columns</td>
            <td>colspan=?</td>
          </tr>
          <tr>
            <td><em>Table border</em></td>
            <td><em>border=? <span class="th">*Deprecated attribute*</span></em></td>
          </tr>
        </tbody>
      </table>
      </section>
      <br><br>
      <section class="form">
        <form action="2ndPage.html" method="POST">
          <h1 style="color: darkblue;">Sign in:</h1>
          <label for="username">Username:</label>
          <input list="list" id="username" type="text" name="username" required minlength="4" maxlength="20">
          <datalist id="list">
            <option value="Dovid"></option>
            <option value="Dave"></option>
            <option value="David"></option>
          </datalist><br><br>
          <label for="pass">Password:</label>
          <input id="pass" type="password" name="password" required minlength="4" pattern="[a-zA-Z]+"><br><br>
          <label for="age">Age:</label>
          <input id="age" name="age" type="number" min="18" step="1"><br><br>
          <label for="vol">Volume:</label>
          <input id="vol" name="volume" type="range"><br><br>
          <label for="ok">Are you Ok?</label>
          <input id="ok" id="yes" name="ok" type="radio" value="yes" required>
          <label for="yes">Yes</label>
          <input id="ok" id="no" name="ok" type="radio" value="no" required>
          <label for="no">No</label><br><br>
          <span>When is your bitrthday?</span><br>
          <input id="check" name="birth" value="yesterday" type="checkbox">
          <label for="check">Yesterday</label>
          <input id="checks" name="birth" value="today" type="checkbox">
          <label for="checks">Today</label>
          <input id="chec" name="birth" value="tommorow" type="checkbox">
          <label for="chec">tommorow</label><br><br>
          <label for="born">Where were you born?</label>
          <select id="born" name="born" required>
            <option value="- -"></option>
            <option value="london">London</option>
            <option value="manchester">Manchester</option>
            <option value="gateshead">Gateshead</option>
            <option value="other">Other</option>
          </select><br><br>
          <label for="ex">Anything to add:</label><br>
          <textarea name="extra" id="ex" cols="30" rows="2" required></textarea><br><br>
          <input type="submit"><br><br><br>
        </form>
      </section>
      <section class="form">
        <form action="2ndPage.html" method="POST">
          <h1 style="color: darkblue;">Sign in:</h1>
          <label for="username">Username:</label>
          <input list="list" id="username" type="text" name="username" required minlength="4" maxlength="20">
          <datalist id="list">
            <option value="Dovid"></option>
            <option value="Dave"></option>
            <option value="David"></option>
          </datalist><br><br>
          <label for="pass">Password:</label>
          <input id="pass" type="password" name="password" required minlength="4" pattern="[a-zA-Z]+"><br><br>
          <label for="age">Age:</label>
          <input id="age" name="age" type="number" min="18" step="1"><br><br>
          <label for="vol">Volume:</label>
          <input id="vol" name="volume" type="range"><br><br>
          <label for="ok">Are you Ok?</label>
          <input id="ok" id="yes" name="ok" type="radio" value="yes" required>
          <label for="yes">Yes</label>
          <input id="ok" id="no" name="ok" type="radio" value="no" required>
          <label for="no">No</label><br><br>
          <span>When is your bitrthday?</span><br>
          <input id="check" name="birth" value="yesterday" type="checkbox">
          <label for="check">Yesterday</label>
          <input id="checks" name="birth" value="today" type="checkbox">
          <label for="checks">Today</label>
          <input id="chec" name="birth" value="tommorow" type="checkbox">
          <label for="chec">tommorow</label><br><br>
          <label for="born">Where were you born?</label>
          <select id="born" name="born" required>
            <option value="- -"></option>
            <option value="london">London</option>
            <option value="manchester">Manchester</option>
            <option value="gateshead">Gateshead</option>
            <option value="other">Other</option>
          </select><br><br>
          <label for="ex">Anything to add:</label><br>
          <textarea name="extra" id="ex" cols="30" rows="2" required></textarea><br><br>
          <input type="submit"><br><br><br>
        </form>
      </section>
      <section class="form">
        <form action="2ndPage.html" method="POST">
          <h1 style="color: darkblue;">Sign in:</h1>
          <label for="username">Username:</label>
          <input list="list" id="username" type="text" name="username" required minlength="4" maxlength="20">
          <datalist id="list">
            <option value="Dovid"></option>
            <option value="Dave"></option>
            <option value="David"></option>
          </datalist><br><br>
          <label for="pass">Password:</label>
          <input id="pass" type="password" name="password" required minlength="4" pattern="[a-zA-Z]+"><br><br>
          <label for="age">Age:</label>
          <input id="age" name="age" type="number" min="18" step="1"><br><br>
          <label for="vol">Volume:</label>
          <input id="vol" name="volume" type="range"><br><br>
          <label for="ok">Are you Ok?</label>
          <input id="ok" id="yes" name="ok" type="radio" value="yes" required>
          <label for="yes">Yes</label>
          <input id="ok" id="no" name="ok" type="radio" value="no" required>
          <label for="no">No</label><br><br>
          <span>When is your bitrthday?</span><br>
          <input id="check" name="birth" value="yesterday" type="checkbox">
          <label for="check">Yesterday</label>
          <input id="checks" name="birth" value="today" type="checkbox">
          <label for="checks">Today</label>
          <input id="chec" name="birth" value="tommorow" type="checkbox">
          <label for="chec">tommorow</label><br><br>
          <label for="born">Where were you born?</label>
          <select id="born" name="born" required>
            <option value="- -"></option>
            <option value="london">London</option>
            <option value="manchester">Manchester</option>
            <option value="gateshead">Gateshead</option>
            <option value="other">Other</option>
          </select><br><br>
          <label for="ex">Anything to add:</label><br>
          <textarea name="extra" id="ex" cols="30" rows="2" required></textarea><br><br>
          <input type="submit"><br><br><br>
        </form>
      </section>
    </main>
    <br>
    <footer>
      <a href="#stik"><img src="top.svg"></a>
      <nav>
        <a href="#top">Home</a>
        <a href="./CSS.html">2nd Page</a>
      </nav>
    </footer>
  </body>
</html>

