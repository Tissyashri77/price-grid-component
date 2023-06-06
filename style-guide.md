# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Cyan: hsl(179, 62%, 43%)
- Bright Yellow: hsl(71, 73%, 54%)

### Neutral

- Light Gray: hsl(204, 43%, 93%)
- Grayish Blue: hsl(218, 22%, 67%)

## Typography

### Body Copy

- Font size: 16px

### Font

- Family: [Karla](https://fonts.google.com/specimen/Karla)
- Weights: 400, 700  




* {
    padding: 0px;
    margin: 0px;
}

.container{
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #E6EFF6;
}

.layout{
    width: 55rem;
    height: 35rem;
    display: flex;
    flex-direction: column;
    border-radius: 10px;
    font-family: karla;
    overflow: hidden;
}

.layout-top{
    background-color: #FFFFFF;
    width: 100%;
    height: 45%;
    display: flex;
    align-items: center;
    justify-content: center;
    
}

.layout-top-content{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 90%;
    gap:20px;
}

.layout-top h1{
     color: #4FB3AF;
     font-size: 32px;
     font-weight:600;
}

.layout-top h2{
    color: #CCDF6B;
}

.layout-top p{
    color: #b5b9bd;
    word-spacing: 2px;
    line-height: 30px;
    letter-spacing: 1.5px;
    font-weight: 400;
    width: 90%;
}

.layout-bottom{
    width: 100%;
    height: 55%;
    display: flex;
}

.layout-bottom-left{
    background-color: #2BB3B1;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    gap: 40px;
}

.layout-bottom-left-content{
    margin: 10%;

    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

.layout-bottom-left-content h1{
    color: #E2FFFF;
    font-weight: 700;
    font-size: 24px;
}
.text1{
    position: relative;
}
.dollor{
    color: #F2FFFF;
    font-weight: bold;
    font-size: 32px;

}
.dollor_text{
    position: relative;
    bottom: 23 %;
    right: -5%;
    font-size: 14px;
    color: #F2FFFF;

   
}

.layout-bottom-left-content h2{
    color: #BDFBF9;
    font-weight: 400;
    font-size: 16px;
    letter-spacing: 1px;
}

/* .layout-bottom-left-content p{
    color:#F2FFFF ;
    font-weight: lighter;
    font-size: 16px;

} */
button{
    color: #FFFFFF;
    width: 100%;
    background-color: #BFDF32;
    text-align: center;
    padding: 20px;
    border-radius: 10px;
    font-weight: bold;
    font-size: 18px;
    border: none;
}

.layout-bottom-right{
    width: 50%;
    height: 100%;
    background-color: #4ABEBD;
}

.layout-bottom-right-content{
    margin: 10%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

.layout-bottom-right-content h1{
    padding-bottom: 10px;
    font-weight: 700;
    color: #E6FEFF;
    font-size: 24px;
    
}

.layout-bottom-right-content p{
    color: #e9eeee;
    line-height: 25px;
    font-weight: 400;
}


@media only screen and (max-width:900px){
    

    .layout{
        border-radius: 15px;
        height: 100%;
        width: 90%;
        margin-top: 150px;
        margin-bottom: 150px;
    }
    
    
    .layout-bottom{
        height: 60%;
        flex-direction: column;
    }

    .layout-top{
        height: 40%;
    }

    .layout-top-content{
        margin: 8%;
    }
    .layout-bottom-left{
        width: 100%;
        height: 50%;
    }

    .layout-bottom-right{
        width: 100%;
        height: 50%;
    }
    .layout-bottom-left-content{
        display: flex;
        flex-direction: column;
        gap:10px;
        margin: 8%;
    }
}