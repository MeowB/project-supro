# project-supro
THE PAGE IS NOW ONLINE [HERE](https://meowb.github.io/project-supro/index.html)

Made with love by :
- [Scott Borlon](https://github.com/MeowB)   
- [Mehdi Semlali](https://github.com/mehdoche1988)   
- [Arthur Pluymers](https://github.com/Buchos)   

This was an exercice for BeCode, the goal was to use what we learned about HTML/CSS/SASS to design 5 pages of a webshop with a picture of the given goal to achieve.   
The pages had to be responsive for desktop, tablet and mobile.   
This was made in our 3rd week at becode in late may/early june.   


## bugs:
* ~~hamburger hitbox~~
Solution: adding  "pointer-events: none;" on everything getting above the toggler checkbox ( class: "header__icon--menuwrap--hamburger")

* when the hamburger menu is toggled, the navbar still scroll trough the page
Solution: getting the menu background div to cover the whole screen and added a higher "z-index" to the cross and the toggler,
new bug is that both of them was disapearing when scrolling down, i couls get the toggler to be fixed while toggle but not the cross.



* ~~footer width right, icons out of page~~
Solution: fixing HTML markup and getting rid of useless divs

* ~~footer list collapsing on small screen~~
Solution: settingup a list wrapper, displaying it as a table and then each lists as a table cell with 'display: " ";' ( class:"footer__listwrap" & "footer__list" )

* ~~footer going through main content~~
fixed, idk how...



