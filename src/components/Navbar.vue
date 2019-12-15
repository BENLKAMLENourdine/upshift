<template>
    <div class="navbar">
        <div class="col-md-12">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" href="#"><img src="../assets/output-onlinepngtools.png" alt=""></a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item current mx-5">
                        <a class="nav-link active" href="#"><span class="circle"></span> Personal <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item mx-2">
                        <a class="nav-link" href="#"><span class="circle"></span> Business</a>
                    </li>
                </ul>
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item mx-3">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item mx-3">
                        <a class="nav-link" href="#">Pricing</a>
                    </li>
                        <li class="nav-item mx-3">
                        <a class="nav-link" href="#">FAQ</a>
                    </li>
                    <li class="nav-item mx-3">
                        <a class="nav-link" href="#">Contact Us</a>
                    </li>
                </ul>
                <ul class="navbar-nav my-lg-0">
                    <li class="nav-item mx-4">
                        <a class="nav-link" href="#">Log In</a>
                    </li>
                    <li class="nav-item join">
                        <a class="nav-link" href="#">Join Now</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
    </div>
</template>
<script>

</script>

<style>
.navbar{
    background: #f6f5f8 !important;
    color: #74758f !important;
    padding-top: 0px !important;
}

.navbar ul li.current{
    border-top: 2px solid #74758f;
}
.navbar-brand{
    font-weight: bold;
    color: #74758f !important;
}
.circle{
    width: 15px;
    height: 15px;
    border-radius: 50px;
    background: #e6e8ea;
    display: inline-block;
    position: relative;
    top: 2px;
    right: 8px;
}
.join{
    margin-top: 2px;
    color: #f6f5f8;
    background: #e6e8ea;
    border: none;
    padding: 2px 25px;
    border-radius: 50px;
}
</style>