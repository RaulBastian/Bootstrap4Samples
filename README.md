# Bootstrap 4 samples

Following bootstrap4 docs and doing a few samples

## Navigation

Navbar:
<https://getbootstrap.com/docs/4.0/components/navbar/>

Color schemes:
<https://getbootstrap.com/docs/4.0/components/navbar/#color-schemes>

> For dark or white backgrounds(Obs: Changes the font color to the oposite)
navbar-dark (light font color)
navbar-light (dark font color)

Brand:
<https://getbootstrap.com/docs/4.0/components/navbar/#brand>

Spacing:
<https://getbootstrap.com/docs/4.0/utilities/spacing/>
"Assign responsive-friendly margin or padding ...."

> Example with margin bottom 0 as h1

    <span class="navbar-brand mb-0 h1" href="#">Navbar</span>

Centering:
<https://getbootstrap.com/docs/4.0/utilities/spacing/#horizontal-centering>

Toggler:
<https://getbootstrap.com/docs/4.0/components/navbar/#toggler>

>collapse (collapses)
>
>collapse navbar-collapse (opposite of collapse)

e.g:

    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse"> 
            <span>Hi there</span>
          </div>
    </nav>

Toggler, hidden content:
<https://getbootstrap.com/docs/4.0/components/navbar/#external-content>

Requires:  
bootstrap.min.js  
jquery

        navigation_bar_hidden_content.html

Menu items:
<https://getbootstrap.com/docs/4.0/components/navbar/#nav>

Requires:
Wrapped in navbar-nav class  
Items have nav-item class  
Links have nav-link class

      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#">Item 1</a>
        </li>
      </ul>

Forms in navbar:  
<https://getbootstrap.com/docs/4.0/components/navbar/#forms>

mr-auto: Makes the form allign to the right

        <ul class="navbar-nav mr-auto">

Can be used with input groups

## input-group

<https://getbootstrap.com/docs/4.0/components/input-group/>
