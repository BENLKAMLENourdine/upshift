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
                        <a class="nav-link active" href="#"><i class="fas fa-user icon"></i>Personal <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item mx-2">
                        <a class="nav-link" href="#"><i class="fas fa-briefcase icon"></i>Business</a>
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
    background: #ffffff !important;
    color: #4d5361 !important;
    padding-top: 0px !important;
    font-weight: bold;
    font-size: 14px;
}

.navbar ul li.current{
    border-top: 2px solid #333456;
    color: #333456 !important;
}
.navbar ul li.current a:active, .navbar ul li.current a:visited{
    color: #333456 !important;
}
.navbar-brand{
    font-weight: bold;
    color: #74758f !important;
}
.icon{
    position: relative;
    right: 10px;
}
.join{
    margin-top: 2px;
    color: #333456;
    background: transparent;
    border: 2px solid rgba(51, 52, 86, 0.3);
    padding: 0 25px;
    border-radius: 50px;
}

.join li .nav-link:active, .join li .nav-link:visited, .join li .nav-link{
    color: #333456 !important;
}
</style>