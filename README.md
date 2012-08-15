#Flexo

Flexo is a mobile-first responsive grid designed to give you a helping hand developing responsive sites. 

Flexo has been designed with simplicity in mind. A five column grid with a sticky footer that scales beautifully up as you go from mobile to desktop. There are multiple column combinations available and columns can also easily be nested.

##The grid

Flexo will default to **1140px** on Internet Explorer versions 7 and 8 and will scale up to the same width in modern browsers. Changing that value is as simple as editing one property in **flexo.css** and **flexo-legacy.css**

Column classes are prefixed with **clmn**  ranging from 1 to 5 with fractional values represented also.

A classic 2-column layout could be coded as follows:

    <div class="row">
        <div class="clmn2"></div>
        <div class="clmn2"></div> 
    </div>

A 3-column layout could be coded as follows:

    <div class="row">
        <div class="clmn5"></div>
        <div class="clmn3-5"></div> 
        <div class="clmn5"></div>        
    </div>
    
A nested column layout could be coded as follows:

    <div class="row">
        <div class="clmn2">
            <div class="row">
                <div class="clmn2"></div> 
                <div class="clmn2"></div> 
            </div> 
        </div>
        <div class="clmn2"></div>        
    </div>
    
Checkout the **index.html** file to see it in action.