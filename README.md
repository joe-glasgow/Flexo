#Flexo

Flexo is a mobile-first responsive grid designed to give you a helping hand developing responsive sites. 

Flexo has been designed with simplicity in mind. A five column grid with a sticky footer that scales beautifully up as you go from mobile to desktop. There are multiple column combinations available and columns can also easily be.

##The grid

Flexo will default to 1140px on ie7 and ie8 and will scale up to that width in modern browsers. Changing that value is as simple as editing one property in **flexo.css** and **flexo-legacy.css**

Column classes are prefixed with **clmn**  ranging from 1 to 5 with fractional values represented also.

A classic 2-column layout would be coded as follows:

    <div class="row">
        <div class="clmn2"></div>
        <div class="clmn2"></div> 
    </div>



Checkout the **index.html** file to see it in action.