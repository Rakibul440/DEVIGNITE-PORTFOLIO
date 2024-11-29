# Portfolio Website

## Style

### Body 

```css
body{
    padding: 0 100px 0 100px;
    display: flex;
    align-items: center;
    background-color: 	#C7EEFF ;
}

```
### Navbar

```css
.navbar{
    width: 100%;
    height: 100px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;

    border-bottom: 1px solid black ;
}
```
### Nav-items 
```css

.nav-items{
    height: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 15px;
}

a{
    text-decoration: none;
    color: black;
}
a:hover{
    color: white;
}
```
### Hero Section

```css

.hero{
    width: 100%;
    padding-top: 50px;
    display: flex;
    flex-direction: row;

    justify-content: space-around;
  
    @media (max-width:430px) {
        flex-wrap: wrap;
        justify-content: center;
    }
    
}

```

```css

/* Style Text */
.identity{
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;

    border-bottom: 1px solid black ;
}
```

```css
.identity h1 {
    text-align: center;
    font-size: 70px;
}

.identity h1 span{
    color: #ff014f;
}

```


```css
/* text */
.identity p{
    font-weight: 500;
    color: rgb(40, 40, 40);
}
.identity p span{
    color: #ff014f;
    
}
```
```css
/* Social Media */

.identity .connect{
    display: flex;
    flex-direction: row;
    justify-items: center;
    align-items: center;
    gap: 10px;
}

```

```css
/* image */
.image{
    width: 700px; 
    border: 0; 
    
    @media (max-width:430px) {
        width: 100%;
    }
}
```
### About
```css
/*------------------- About -----------------*/
.about{
    width: 100%;
    padding: 10px;
   

    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;

    gap: 100px;

    border-bottom: 1px solid black ;


    @media (max-width:430px) {
        flex-direction: column-reverse;
        gap: 30px;
    }


}

```

```css
/* About-Text Style */
.about-head{
    color: #ff014f;
    text-align: center;
    padding-bottom: 10px;
}
.about-text{
    text-align: center;
}
.about-text span{
    color: #ff014f;
    font-weight: bold;
}
/* Style About Image */
.about-img{
    width: 250px;
    border-radius: 50%;
    border: 2px solid #ff014f;

}

```

### Features

```css


.features{
    padding-top: 30px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;


    padding-bottom: 30px;

    border-bottom: 1px solid black;
}

.features-text p{
    color: #ff014f;
    padding-bottom: 20px;
}

.features-text h1{
    color: white;
}

```

```css

/* Service */
.service{
    padding-top: 30px;
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    text-align: center;
    gap: 30px;

    flex-wrap: wrap;
}

```

```css
/* Style Box */
.box{

    width: 400px;
    height: 300px;
    background: #9be1ff;
    padding: 30px;
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-items: center;
    gap: 20px;

    border-radius: 5px;
    box-shadow: 2px 2px 5px rgb(232, 232, 232);
}
.box:hover{
    background-color: #C7EEFF;
    border: 1px solid white;
}
.box h1{
    color: #ff014f;
}
.box p{
    color: beige;
}

.box svg{
    width: 30px;
}
```

### Footer

```css

/* Footer */

footer{
    height: 100px;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
}

```