# Media Queries

This setup is for media queries and its use.

```
/* This part is for the media to arrange */
@media screen and (max-width: 800px){
    
    body{background: orange;}
    h1{font-size: 40px;
        color: #1010d3;}
    span{font-size: 40px;}
    p{font-size: 10px;}

}

@media screen and (max-width: 600px) and (min-width: 400px) {
    body{background: crimson;}    
    h1{font-size: 40px;}
    span{font-size: 40px;
        color: #ffffff;}
    p{font-size: 10px;}
}
```