# project-supro
THE PAGE IS NOW ONLINE [HERE](https://meowb.github.io/project-supro/index.html)
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



