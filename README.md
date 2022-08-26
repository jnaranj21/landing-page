# landing-page
Photo by zhang kaiyv: https://www.pexels.com/photo/time-lapse-photography-of-brown-concrete-building-842654/

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Rubik+Iso&display=swap');

*{
    color: #f9faf8;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

header{
    display: flex;
    flex-flow: row wrap;
    background-image: url(images/fast.jpg);
    background-position: center;
    background-size: cover;
    height: 540px;
}

nav{
    width: 100%;
    height: 60px;
    background: linear-gradient(to right, rgba(0,0,0,0), rgba(0,0,0,1));
    display: flex;
    align-items: center;
}

ul{
    display: flex;
    list-style: none;
}

a{
    display: flex;
    text-decoration: none;
    font-size: 20px;
    margin-right: 90px;
    justify-content: flex-end;
}

.disclaimer{
    display: flex;
    font-style: italic;
}

.book{
    font-size: 18px;
    padding: 8px 21px;
    border: none;
    border-radius: 5px;
    background-color: #c01864;
    color: #f9faf8;
    margin-right: 50px;
}

.logo{    
    font-family: 'Rubik Iso';
    font-size: 39px;
    font-weight: bold;
    padding-top: 36px;
    margin: 120px;
    color: rgb(237, 185, 0);
}

.sub{
    font-family: 'Roboto';
    font-size: 20px;
}

.hero{
 height: 350px;
 width: 550px;
 background: linear-gradient(to bottom, rgba(0,0,0,0.0), rgba(0,0,0,0.9), rgba(0,0,0,1)); 
 display: block;
 margin-top: 20px;
 margin-left: 700px; 
 padding: 20px 20px 0px; 
}

.one{
    font-family: 'Roboto';
    font-size: 45px;
}

.special{
    float: right;
    transform: translateX(-30px) translateY(25px) rotate(15deg);
    font-family: 'Rubik Iso';
    font-size: 39px;
    font-weight: bolder;
}

.two{
    font-size: 24px;
    margin-top: 12px;
}

.three{
    margin-top: 20px;
}

input{
    height: 34px;
    border: none;
    border-radius: 5px;
    margin-right: 5px;
    width: 350px;
    font-size: 18px;
    padding: 6px 21px;
}

.send{
    height: 34px;
    font-size: 18px;
    font-weight: bold;
    padding: 6px 21px;
    border: none;
    border-radius: 5px;
    background-color: #ade200;
    color: black    
}

.infosection{
    display: flex;
    height: 380px;
    background-image: url(images/trippy.jpg);
    background-position: center;
    background-size: cover;
    margin-top: 1px;
}

.transparency{
    height: 260px;
    width: 75%;
    background: linear-gradient(to right, rgba(0,0,0,0), rgba(0,0,0,0.6), rgba(0,0,0,.9));
    display: flex;
    margin: auto;
}


