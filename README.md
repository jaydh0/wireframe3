# wireframe3
New Wireframe
#mainwrapper{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}

#mainwrapper{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 0.3fr 0.7fr 0.3fr 0.8fr 0.3fr 0.5fr ;
    grid-template-areas: 
    "sub1 sub1 sub1"
    "par1 par2 par3"
    "sub2 sub2 sub2"
    "par3"
    "sub3 sub3 sub3"
    "par5 par6";

}

.section1, .section2, .section3{
    background-color: rgb(9, 125, 125);
    
}

.sub1{
    background-color: aqua;
}

.par1{
    background-color: blue;
}

.sub2{
    background-color: cornflowerblue;
}


.footerdiv{
    background-color: aquamarine;
    grid-area: footer;
}