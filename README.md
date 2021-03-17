<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Pedro's 8-bit Resume</title>
    <!-- latest -->
    <link href="https://unpkg.com/nes.css@latest/css/nes.min.css" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Press+Start+2P" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/flexboxgrid/6.3.1/flexboxgrid.min.css" type="text/css">
    <style>
        body {
            padding-bottom: 50px;
        }
        .nes-progress {
            height: 25px;
        }
    </style>
</head>

<body>

    <!-- Navigation bar -->
    <nav style='padding: 20px; border-bottom: 3px solid #ccc; margin-bottom: 80px;'>
        <div class="container">
            <h2 style='margin-bottom: 0;'>
                Pedro Forastieri de Almeida Prado    (+11 961962700)
            </h2>

        </div>
    </nav>

    <!-- Welcome "banner"/NES Balloon -->
    <div class="container" style='margin-bottom: 50px;'>
        <div class="row bottom-md bottom-xs">
            <div class="col-xs-2">
                <img src="https://avatars.githubusercontent.com/u/67510604?s=400&u=f58e753a24bad63e828cd0f46f9f9b2c927863b6&v=4.png" style='width: 100%; height: auto; image-rendering: pixelated; image-rendering: -moz-crisp-edges; '>
            </div> 
            <div class="col-sm-9 col-xs-12">
                <div class="nes-balloon from-left">
                    <p>I'm Pedro Forastieri and this is what you should know about me! <i class="nes-icon is-small heart"></i></p>
                </div>
            </div>
        </div>
    </div>

    <!-- Main body content; 2 columns -->
    <div class="container">
        <div class="row">
            <!-- Main left column -->
            <div class="col-md-4 col-sm-15 col-xs-12">
                <section class="nes-container with-title">
                    <h3 class="title">Things I Do</h3>
                    <div>
                        <div class="lists">
                            <ul class="nes-list is-circle" style='margin-bottom: 0;'>
                                <li>Data Scientist</li>
                                <li>Stats Blackbelt</li>
                                <li>Chemical Engineer</li>
                                <li>Musician by night</li>
                            </ul>
                        </div>
                    </div>
                </section>

                <section class="nes-container with-title" style='margin-top: 50px; margin-bottom: 50px;'>
                    <h3 class="title">Data Analysis skills</h3>
                    <div>
                        <p>
                            <i class="nes-icon is-small star"></i>
                            Python:
                            <p>
                                Pandas, Numpy, BeautifulSoup, Databricks, Scikit-learn, Pytorch, PySpark.
                            </p>
                        </p>
                        <p>
                            <i class="nes-icon is-small star"></i>
                            Postgres & MySQL
                        </p>
                        <p>
                            <i class="nes-icon is-small star"></i>
                            Tableau, Seaborn, Matplotlib, Altair, Plotly
                        </p>
                        <p>
                            <i class="nes-icon is-small star"></i>
                            Data and ML pipelines / ETLs
                        </p>
                        <p>
                            <i class="nes-icon is-small star"></i>
                            Matlab & Scilab
                        </p>                      
                    </div>
                </section>

                <section class="nes-container with-title" style='margin-top: 50px; margin-bottom: 50px;'>
                    <h3 class="title">Noteworthies</h3>
                    <div>
                        <i class="nes-icon is heart"></i>
                        "Leanifique" Six Sigma teaching co-founder
                    </div>
                    <div>
                        <i class="nes-icon is trophy"></i>
                        Self-taught guitarist and bass player
                    </div>
                    <div>
                        <i class="nes-icon is coin"></i>
                        Traveling makes my budget
                    </div>
                    <div>
                        <i class="nes-icon is-small snes-jp-logo"></i>
                        Homemade Raspberry Pi arcade<a href="https://youtu.be/PVkc2yqv_gk"><h4 class="title">check here</h4></a>
                    </div>
                </section>
                
                <section class="nes-container with-title" style='margin-top: 50px; margin-bottom: 50px;'>
                    <h3 class="title">Languages spoken</h3>                    
                    <div>
                        <div class="lists">
                            <ul class="nes-list is-circle" style='margin-bottom: 0;'>
                                <li>English</li>
                                <progress class="nes-progress is-primary" value="90" max="100"></progress>
                                <li>Spanish</li>
                                <progress class="nes-progress is-primary" value="90" max="100"></progress>
                                <li>German</li>
                                <progress class="nes-progress is-warning" value="30" max="100"></progress>
                                <li>Italian</li>
                                <progress class="nes-progress is-error" value="10" max="100"></progress>
                            </ul>
                        </div>
                    </div>                                     
                </section>

                <section class="nes-container with-title" style='margin-top: 50px; margin-bottom: 50px;'>
                    <h3 class="title">My Socials</h3>
                    <div>                        
                        <a href="https://www.linkedin.com/in/pedroforastieri/">
                            <i class="nes-icon linkedin"></i>
                        </a>
                        <a href="https://github.com/Forastierii/">
                            <i class="nes-icon github"></i>
                        </a>
                        <a href="https://medium.com/@pfaprado">
                            <i class="nes-icon medium"></i>
                        <a href="https://facebook.com/pfaprado/">
                            <i class="nes-icon facebook"></i>
                        </a>
                    </div>
                    <div>
                        <a href="mailto:pfaprado@gmail.com">
                            <h4 class="title">pfaprado@gmail.com</h4>
                        </a>
                    </div>
                    <div>
                        +55 11 961 962 700
                    </div>                    
                </section>

            </div>
            <!-- Main right column -->
            <div class="col-md-8 col-sm-12 col-xs-12">                
                <div class="nes-container with-title is-dark" style='margin-top: 0px;'>
                    <p class="title">Education</p>
                    <div class="row">
                        <div class="col-sm-20 col-xs-12">
                        <pre>2021: Data Analytics (+500h bootcamp)
            <i class="nes-icon is-small heart"></i>IronHack São Paulo</pre>
                        </div>                        
                    </div>                    
                    <div class="row">
                        <div class="col-sm-20 col-xs-12">
                        <pre>2018: Lean Six Sigma Blackbelt
            SETA Desenvolvimento Gerencial</pre>
                        </div>
                        </div>
                    <div class="row">
                        <div class="col-sm-25 col-xs-12">
                        <pre>2017: Master of Sc. in Chemical Engineering
            Universidade de São Paulo</pre>    
                        </div>                        
                    </div>
                    <div class="row">
                        <div class="col-sm-25 col-xs-12">
                        <pre>2014: Bachelor of Sc. in Chemical Engineering
            Universidade Federal São Carlos</pre>    
                        </div>                        
                    </div>
                    <div class="row">
                        <div class="col-sm-25 col-xs-12">
                        <pre>2013: Exchg. Scholarship: Engineering Science
            University of Toronto / Canada</pre>    
                        </div>                        
                    </div>
                </div>
                
                <h3 class="topic-title" style='margin-top: 40px;'>
                    <i class="nes-icon star"></i> Previous Experience
                </h3>
                <section class="nes-container is-dark">
                    <div class="row">
                        <div class="col-xs-2">
                            <img src="data:image/png;base64,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" style='width: 100%; height: auto; image-rendering: pixelated; image-rendering: -moz-crisp-edges; '>
                        </div>
                        <div class="col-xs-10">
                            <h3>Berry Global</h3>
                            <p>Black Belt Process Engineer</p>
                            <div>
                                <a href="https://github.com/Forastierii/blackbeltproject/blob/main/BB%20Project%20-%20Pedro%20Prado%20(compressed).pdf">
                                    <i class="nes-icon github"></i>
                                </a>                                
                            </div>
                            <h10>
                            <p>- Implemented an image recognition system (QuickTeach) for defects identification on products - training in Atlanta/USA</p>
                            <p>- Developed projects on database restructuring in tandem with IT area for KPIs Dashboard (BIS) and Tableau/PowerBI implementation</p>
                            <p>- Developed dashboards with Pivot tables/charts and primary key/foreign keys in Postgre</p>
                            <p>- Controlled processes with statistical tools: distributions, linear and multilinear regressions, control charts, time series charts, Ishikawa, hypothesis test (A/B) to establish sound action plans (5W2H)
                            <p>- Increased production efficiency (First Pass Yield) from 83% to 87% and savings of up to 10k USD/month with scrap reduction</p>
                            <p>- Managed a production line of up to 50 tons/day</p>
                            <p>- Facemask Machine installation and support in Brazil and China</p>
                            <p>- Training courses in Atlanta (USA), Pilar (ARG) e Cali (COL)</p>
                            </h10>
                        </div>
                    </div>
                    <div class="row" style='margin-top: 30px;'>
                        <div class="col-xs-2">
                            <img src="data:image/png;base64,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" style='width: 100%; height: auto; image-rendering: pixelated; image-rendering: -moz-crisp-edges; '>
                        </div>
                        <div class="col-xs-10">
                            <h3>Berry Global</h3>
                            <p>Lean Six Sigma Specialist</p>
                            <div>
                                <a href="https://github.com/Forastierii/yellowbeltpipeline/blob/main/Apresenta%C3%A7%C3%A3o%20Yellow%20Belts%2001-02-2018.pdf">
                                    <i class="nes-icon github"></i>
                                </a>                                
                            </div>
                            <h10>
                                <p>- Lean Six Sigma statistical methodology to solve business challenges in both administrative and industrial areas</p>
                                <p>- Black Belt Lean Six Sigma certified (1-month training, 2-year project)</p>
                                <p>- Established the Yellow Belt program in Berry, training and managing 27 concurring projects in many areas using statistics: logistics, production, finance, HR and IT – running 14 of them at the same time.</p>
                                <p>- Developed a project on raw materials recycling using Minitab: U$40k USD/month savings</p>
                                <p>- Daily contact with overseas plants: Tarragona (Spain) and Statesville (USA) for best practices exchange and statistical methods</p>
                            </h10>
                        </div>
                    </div>
                    <div class="row" style='margin-top: 30px;'>
                        <div class="col-xs-2">
                            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJcAAABbCAMAAABJa+eEAAABEVBMVEX////+/v77xwcyvPE8U2EzTFs6UWAvSVg3T10sR1dgcn5PZHG85vr6vwiWoKcfufH6twm6wcb4sAqgqK74og34qQzT19mlr7Upl9n3nA3Jz9Pv8fL2kg90g43m6eowtOz2iBErn97zXgD0gBJ+jJWxuL3c4OJFW2kAdMUjgssmi9EgQFItqOTo9vz5up/3oXn3qnr4tXn6vXj6xXf7z3b82nn96J/+9t796uPzaAD8zzf96K35wav0cxT80kz60br/++784Mv2lCv3nzf4rUL+9ND4uFnv0IWyqHGoxeeLl3x5jouCqdcAZcKFlIj84pFpjp1Wg6LqwRf/2F+41u58vehZm9QAMUZfxvOD1PbQ7/uHdlYXAAAKa0lEQVRoge1Xe59bNxGd2dV92cGLa7DDNXaa4MduvIaUJKRpC6SFFgItUJpCst//gzCSrqQZSdfrzaYtf1S/xOtzrx5HM2eOZABA88/8B6QGoaF/4SAyCPKthXZ8eNNBhPDCQfTjUmiY2GZZYbc+upfQ/UcGwygP4y4ou2QhoPgL+QHi+3VPv+vmssUC7yDEELsgiywmsH+8l0YMMQO7xLocW67dR5cVn5wMxBi6Z3bO7juD6HPvIWQgkwuE52E1kFDqCxgEDtkmE+iKJ4Vs6yzOrh59YTHSLsCMVwQxgZCBaQ7Af0goeIL4xqqEFSCLbA9kzyDqcqAAI8hVy1oGIvvsg06zcppbQB9kNjNyq3MQvQ37wHeF5FIkiyiFXF8SunzFUfk/a76MgWlc6B6u170/LFil9EDogcgX5rq/VQP5jbHuhSG7KfSB8h/AoNAXeH2FKPdBkAOPgjEF7jCIoax8YIM2mfi9kbodBGsKndle5Bj/IILoYBBSVDPOwQIvF2yvRAGBQV5xEnJeCeRTCF/t4tUrlxtAptmMhK+HByv1B27ordIilLXg3vb4PXKIvvohzPCW0MkgzQawNL3NB8j5pF58frMw8kSM6xF9TIJGXbG51Vw9emmEyQI8xJHv383pl5b0fLTkKvxZCvEaiBEM3pJAUY8gvrHeLMd8Y3nInsko3QQK/w3y66+RnKPLEuqf67qp06nYGcDrgx8NTngHIXq5OXsPndCPAfz1bx49evTBB799/PjxkydPn/7uGbOE/nPr8D4Obvq49uGDB8+f/+r993/5i5/9/L2f/uTk5OSjj3PrhpB5/3Gqip4hgyC7SMijgzx25v8nD57/XvA6OfnDM76ILJZDLdJ+v/hZifnyiSF8kvA6+egZ8wuRHeQx5Bp+l6nsBv8x4XVy8iKlwOIPLGvsrEEfYn8C+f7SaOWlQkA3CbVPU15PRSU5YiHIGV4o/V4YbQI9A8xAP+bTz2JeJ5+Ht0E50dEgZCXVAxl4lMGL2eHDz2Je3yT6+kHaiz9FvE7k+9T1MfMRu9xh2Nt4nxd/jnh9Hrq5+G4WXVtNprEnsBbbw2ixGB9nNLnJXnwheX0cTmjslDlt6q5VajUH5zWhHvO6HxbNiN9zALlmAwzvkY0H/CLh5Y6wbuS0UKpoqqYqStUsmAB5lCDR/bAsRoeF3qf7Dj55L46X1D3xqmdjapMhEWuPUIpphtet2l+y+vKaJl7VxnzfVKqYhdfBSAHCVpz/dby4IbMryREQ8K+8HuO3mlexscNorcmxxSXiJX0nP4E/U3ypv/xbMHxmDd3XEC9Uqlqbb5tp27ZT/WhKdTeh1wR1/01r2jzkcWMhLNerxWptJ1rqzpvxaGLwvJ2NJtPIWXTbX/y94/VM8ne8iqmW4nxU1Gqu9zPaVk3TFDTloi50nY6W5W6AsFyoRrfduuNFq2+b3ZB4zYZU1gX11OGY7NSG5iiKRk2gHVZVUdWLOXjdu3Puy6/+YWj908Uz0r0a6KYKNdQxgllTqpIIAQ50rVZVXQy2JfHSUBtKo3kpHa/lsK41rVFT1norqlnR1JNCDYq6oAKnTqooaL+qWqXpfXX+1b/MKSTC1XGfdovVZam2Ex3EAU2zoKzQaqoejsbrRV2qeoDLnSqHK2qLaRev+ZZoLQHWjSpW4007ovVnhlddLkajhZl6MBqtiGGz5DZsYnN1fn7+9b+/YbcSLzPLa2taSdtdIMxpyZVOx3JYlnpVwEmleW12pl6tnWletINSkYTmg7qemOnG1BE1r8rscFUrnUBKQa2asdQ9fe7PLy7Ov17yW1CnLxuvop3rNqVpmhnxUtVY92j1G6sFIjBArGjbo6kdOyzr1YIyNTVHhhqOTalMt9oCiVdhdj4uNKTe860OpL/2dBLTvC7OL/b+KhTz2nTJpYQN5sSrMbwmFSHbc11QvGCsipK+tDZeSiferDqrlCKkm0nkpCiHJjJtrXYmHJQDyyuQov+vLh5qYg/3TPf+aLA+YQmvK7Xd0Bw65nQ0F7aKUG9c8wKKaFHW1cD4hOG1sR1VWbhGxybnZWTleDF96affPqRGxL7056jjBZLXmPEy8RrObfGuK82LvixH20ZVAx2vckC53Br1kA20Y9Padrx0vCDDy5/NOo3371piF68AfS5ZPWpfNcuvamJi9UWwray+UJeo9glrOzPS0MacDdO6rHXsWsMaOpudW156HOOlZLz025d3ddPM/iOuyd09J+hrTX6zCLpfbpUVmPaB0q0MSPqbWp+gvFcjo57C1uN01/x3mejL8fL+ZBbeX96/f98yM9JP7znlwrgSZaik0Nk86l7av8pZO140OjC4HJj747BWxbI7h0hZpCdY71S1aKctwWoF/frit6D9vcvLy46YTmTO7+29UP8dQ4gX+ZL2e7LrerAlXu2u69bQaWP9HlcUbUr6inyLvIqADnCkLzDx4lcVavvX9zQxG7OHL+OjAHXoK9ua3aA16TMHoCW2I1JFs1qWzZB42W7afIE66XN7PqTjkjxsRPdKOnl2xkUnu2Zrlm8bnVbdjbpP+LVj//rs7N49GzJi9hLC9adz3/nYNXMvoEdUWnM3vh2tViN9nxhPXU/djVI0HhtV6ofaauczOrkm3X2COvm5rZSp+5I559Xp2enp6ZkL2d1XEPlqEr7ke+43XXjmTjNkO0Xxzv1OCCOI1mtNizG7w1a2Z6T/NQD+Z0b4AQHursqNuBc6z/bV3gf3px0tajaZ+/Se8/23O4GVZXb5bXgprxzu1ML0MYP899BBiBnoH0e0dDKvMvccSCQRbuDsd0cGhr6IciBXHdMzZqKleb3J3HNCnNzYcM9l0P1yDcGFYNAcdqlIYffsTULr9HTv5Cl5uUNTaBn8t8OJgxzEPgg9tMKy6DIVUuivjawuXZWzzHAIHAqXybY0Wmdnb/ZcEXwzIP7EQj0aXq972J/Jdvr6zRW4609u3u+nAV7dEe1qD5ndgFezfcKS51QHIbVCxQGyuuC1kMI+zwxG7sqIOblH353u0+ni3DGxH92uGYDvDAbODoVwI4coN9UPb1s3LsqBLEruEgrv7vP76NzADMQEijUDlH7PzChYlvuDgog4EtxpwQ6rDgndh0lS6NR+c3X92CDVHEg1Hnb0wxAz8N3rnknnKN2jn1s8PQpK3XvheiGDUzjzc69i5JM6yAwemd+HB2IMJ8LqJuLlHevmfh8l7nZ+H5kHU10ORiV8GN62RTwPSPFY+G50jy6TIorh+wHimfxDyIwQkIfoO0QQkc/m9BW6hcMhMeawXAyZTLjuIQeddtjyvqf3ex8tFhzOCyUvlLyQ8YrrMUSX75lHMoFsCi9oX63dVvy2GPQbhT4YRMHnhgyUgzGdK5UNsmihDxrL//EQ4VqIkIUgixuRI+DvO23GLojIIAQYxvMpXPDyEAX0egvLBN2DhEG5+TK4TvciZ2EjvPSiSP3YbtQyhwrkIMpXeShH49tBVr8ovgUvCEl3ggneJ0Tr7I/pi7MVsuW+GogwiGw95qu82Jz18nr0DzgMRFDy4gXjeUeQl/z/AN3Am0MAGNeaAAAAAElFTkSuQmCC" style='width: 100%; height: auto; image-rendering: pixelated; image-rendering: -moz-crisp-edges; '>
                        </div>
                        <div class="col-xs-10">
                            <h3>Braskem</h3>
                            <p>Automation Engineering Intern</p>
                            <div>
                                <a href="https://github.com/Forastierii/braskemautomation/blob/main/Projeto%20Aplicativo%20-%20Pedro%20Forastieri.pdf">
                                    <i class="nes-icon github"></i>
                                </a>                                
                            </div>
                            <h10>
                                <p>- Proposed a regression equation for product quality prediction</p>
                                <p>- Developed a control loop and optimized the PID parameters in Siemens system to solve an excessive hydrogen consumption issue</p>
                                <p>- Provided support in English for overseas Braskem plants: La Porte, Oyster Creek e Marcus Hook (EUA)</p>
                            </h10>
                        </div>
                    </div>
                </section>
            </div>
        </div>
    </div>

    <div class="container" style='margin-top: 50px; font-size: 60%;'>
        <div class="row">
            <div class="col-xs-12" style='text-align: center; color: #ccc;'>
                If are reading this, it means you are really detail-oriented and I sent my CV to the right place ;)
            </div>
        </div>
    </div>

</body>

</html>
