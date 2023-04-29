<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Document</title>
</head>
<style>
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    overflow: hidden;
    height: 100vh;
    background-image: url(https://viettelinternet24h.com/wp-content/uploads/2022/08/img_630afc9011c82.jpg);
    background-size: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}
.search-box{
    background: linear-gradient(to right, #e7461e,#374272);
    width: 70px;
    height: 70px;
    overflow: hidden;
    position: relative;
    border-radius: 15px;
    transition: all 0.5s ease;
}
.search-input{
    width: 100%;
    height: 100%;
    background: transparent;
    padding: 20px 100px 20px 20px;
    font-size: 35px;
    outline: none;
    color: white;
    border: none;

}
.search-btn{
    position: absolute;
    right: 0;
    top:0;
    width: 70px;
    height: 70px;
    font-size: 25px;
    border: none;
    outline: none;
}
.search-btn:hover{
    transform: scale(1.5);
    background-color: #5d6dbb;
    background-image: linear-gradient(43deg, #5d6dbb 0%, #caa9c7 46%, #e9c78b 100%);
}
.search-box.open{
    width: 400px;
}
</style>
<body>
    
    <title>Secarch-boxs</title>
</head>
<body>
    <div class="search-box">
        <input type="text" class="search-input">
        <button class="search-btn">
            <i class="fa-solid fa-magnifying-glass"></i>
        </button>
    </div>
<script>
    var btnSearch = document.querySelector('.search-btn')

    btnSearch.addEventListener('click', function(){
        this.parentElement.classList.toggle('open')
        this.parentElementSibling.focus();
    })
</script>
</body>
</html>

</body>
<script>
    var btnSearch = document.querySelector('.search-btn')

    btnSearch.addEventListener('click', function(){
    this.parentElement.classList.toggle('open')
    this.parentElementSibling.focus();
    })
</script>

</html>
