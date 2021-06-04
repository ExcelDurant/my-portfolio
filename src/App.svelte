<script>
	// export let name;
	import * as animateScroll from "svelte-scrollto";
</script>

<svelte:head>
	<link
		rel="stylesheet"
		href="https://use.fontawesome.com/releases/v5.13.0/css/all.css"
		integrity="sha384-Bfad6CLCknfcloXFOyFnlgtENryhrpZCe29RTifKEixXQZ38WheV+i/6YWSzkz3V"
		crossorigin="anonymous"
	/>
	<link
		rel="stylesheet"
		href="https://use.fontawesome.com/releases/v5.0.7/css/all.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
	/>
	<link
		href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@100;300;400;500;700;900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,800;1,100;1,300&display=swap"
		rel="stylesheet"
	/>

	<link rel="preconnect" href="https://fonts.gstatic.com" />
	<link
		href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,800;1,100;1,300&display=swap"
		rel="stylesheet"
	/>
	<link rel="preconnect" href="https://fonts.gstatic.com" />
	<title>Portfolio</title>
</svelte:head>

<div class="full-page">
	<header class="header">
		<nav class="navbar">
			<div class="logo-container">
				<h2 class="logo-txt">g-e</h2>
			</div>
			<ul class="navlist">
				<!-- svelte-ignore a11y-invalid-attribute -->
				<!-- svelte-ignore a11y-missing-attribute -->
				<li><a on:click={() => animateScroll.scrollTo({element: '#excel'})} class="navlink">excel</a></li>
				<!-- svelte-ignore a11y-invalid-attribute -->
				<!-- svelte-ignore a11y-missing-attribute -->
				<li><a on:click={() => animateScroll.scrollTo({element: '#service'})} class="navlink">services</a></li>
				<!-- svelte-ignore a11y-invalid-attribute -->
				<!-- svelte-ignore a11y-missing-attribute -->
				<li><a on:click={() => animateScroll.scrollTo({element: '#portfolio'})} class="navlink">portfolio</a></li>
				<!-- svelte-ignore a11y-invalid-attribute -->
				<!-- svelte-ignore a11y-missing-attribute -->
				<li><a on:click={() => animateScroll.scrollTo({element: '#tools'})} class="navlink">tools</a></li>
				<!-- svelte-ignore a11y-invalid-attribute -->
				<!-- svelte-ignore a11y-missing-attribute -->
				<li><a on:click={() => animateScroll.scrollTo({element: '#contact'})} class="navlink">contact</a></li>
			</ul>
		</nav>
	</header>

	<section class="home-sec">
		<div class="home-container">
			<div class="txt-container">
				<div class="overlay">
					<h2 class="header-txt">do with passion</h2>
					<h1 class="title">
						design & develop <br />beautiful wep apps
					</h1>
					<p class="txt">
						Lorem ipsum dolor sit amet consectetur <br /> adipisicing
						elit. Natus eaque qui delectus explicabo temporibus.
					</p>
					<div class="icons-container">
						<a
							href="https://github.com/ExcelDurant"
							target="_blank"
							class="icon-link"
							><img
								src="./../assets/img/github.svg"
								class="full-img"
								alt=""
							/></a
						>
						<a
							href="https://twitter.com/DurantExcel"
							target="_blank"
							class="icon-link icon-left twitt"
							><img
								src="./../assets/img/twitter.svg"
								class="full-img"
								alt=""
							/></a
						>
						<a
							href="https://www.instagram.com/troptop_ex/"
							target="_blank"
							class="icon-link icon-left insta"
							><img
								src="./../assets/img/instagram.svg"
								class="full-img"
								alt=""
							/></a
						>
						<a
							href="https://www.linkedin.com/in/excel-gnopa-b5a8161b3/"
							target="_blank"
							class="icon-link icon-left linkin"
							><img
								src="./../assets/img/linkedin.svg"
								class="full-img"
								alt=""
							/></a
						>
					</div>
				</div>
				<h2 class="bg-title">modern</h2>
			</div>
			<div class="logo-container">
				<h2 class="logo-txt">g-e</h2>
			</div>
		</div>
	</section>

	<section class="excel-sec" id="excel">
		<div class="excel-container">
			<div class="img-container">
				<img
					src="./../assets/img/profile.png"
					alt=""
					class="full-img"
				/>
			</div>
			<div class="txt-container">
				<div class="overlay">
					<h3 class="header-txt">Full-stack Web Developer</h3>
					<h2 class="title">
						hi, my name is <br /> Excel Durant
					</h2>
					<p class="txt">
						Lorem, ipsum dolor sit amet consectetur adipisicing
						elit. Debitis cum at a rem quod! Nam natus est eaque
						officia. Ullam ut hic consequatur? Totam tenetur
						voluptatem, nisi veritatis eos nam! Libero accusantium
						nesciunt sit? Voluptates aut illo incidunt earum
						explicabo culpa voluptas odio, eveniet officiis ipsum
						laboriosam consequuntur doloremque deserunt quae aliquid
					</p>
				</div>
				<h2 class="bg-title">about <br />me</h2>
			</div>
		</div>
	</section>

	<section class="service-sec" id="service">
		<div class="service-container">
			<div class="txt-container">
				<h2 class="bg-title">my <br />services</h2>
				<div class="overlay">
					<div class="logo" />
					<div class="titles">
						<h3 class="title">services</h3>
						<p class="txt">
							Lorem ipsum dolor sit amet consectetur adipisicing
							elit. Magni blanditiis laborum rem architecto omnis!
						</p>
					</div>
				</div>
			</div>
			<div class="services">
				<div class="service-card">
					<h4 class="card-title">Web Frontend</h4>
					<p class="card-txt">
						Lorem ipsum dolor sit amet consectetur adipisicing elit.
						Nihil, maxime.
					</p>
				</div>
				<div class="service-card">
					<h4 class="card-title">Content Management</h4>
					<p class="card-txt">
						Lorem ipsum dolor sit amet consectetur adipisicing elit.
						Nihil, maxime. Lorem ipsum dolor sit amet consectetur
						adipisicing elit. Accusamus quasi doloremque suscipit.
					</p>
				</div>
				<div class="service-card">
					<h4 class="card-title">Web Backend</h4>
					<p class="card-txt">
						Lorem ipsum dolor sit amet consectetur adipisicing elit.
						Nihil, maxime. Lorem ipsum dolor sit amet consectetur
						adipisicing.
					</p>
				</div>
			</div>
		</div>
	</section>

	<section class="portfolio-sec" id="portfolio">
		<div class="portfolio-container">
			<div class="txt-container">
				<h2 class="bg-title">my <br />portfolio</h2>
				<div class="overlay">
					<div class="logo" />
					<div class="titles">
						<h3 class="title">portfolio</h3>
						<p class="txt">
							Lorem ipsum dolor sit amet consectetur adipisicing
							elit. Magni blanditiis laborum rem architecto omnis!
						</p>
					</div>
				</div>
			</div>
			<div class="works-grid">
				<a
					href="https://exceldurant.github.io/blogr/"
					target="_blank"
					class="work-card-link"
				>
					<div class="work-card">
						<img src="./../assets/img/mentor1.png" alt="" />
					</div>
				</a>
				<a
					href="https://troptop-quiz.netlify.app"
					target="_blank"
					class="work-card-link"
				>
					<div class="work-card">
						<img src="./../assets/img/quiz.png" alt="" />
					</div>
				</a>
				<a
					href="https://exceldurant.github.io/Quiz-game/"
					target="_blank"
					class="work-card-link"
				>
					<div class="work-card">
						<img src="./../assets/img/quiz2.png" alt="" />
					</div>
				</a>
				<a
					href="https://akylas.netlify.app"
					target="_blank"
					class="work-card-link"
				>
					<div class="work-card">
						<img src="./../assets/img/akylas.png" alt="" />
					</div>
				</a>
				<a
					href="https://actipoten-blog.netlify.app"
					target="_blank"
					class="work-card-link"
				>
					<div class="work-card">
						<img src="./../assets/img/actiblog.png" alt="" />
					</div>
				</a>
				<a
					href="https://exceldurant.github.io/interactive-pricing-component/"
					target="_blank"
					class="work-card-link"
				>
					<div class="work-card">
						<img src="./../assets/img/slider.png" alt="" />
					</div>
				</a>
			</div>
		</div>
	</section>

	<section class="tools-sec" id="tools">
		<div class="tools-container">
			<div class="icons-container">
				<div class="icon-container">
					<img
						src="./../assets/img/html.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/css.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/jslogo.webp"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/sass.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/bootstrap.svg"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/svelte.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/vueLogo.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/nuxt-icon.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/angular.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/firebase.svg"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/node.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/mongo.png"
						alt=""
						class="full-img"
					/>
				</div>
				<div class="icon-container">
					<img
						src="./../assets/img/mysql.png"
						alt=""
						class="full-img"
					/>
				</div>
			</div>
			<div class="txt-container">
				<h2 class="bg-title">tools<br />I use</h2>
				<div class="overlay">
					<div class="logo" />
					<h3 class="title">tools</h3>
					<p class="txt">
						Lorem ipsum dolor sit amet consectetur adipisicing elit.
						Magni blanditiis laborum rem architecto omnis!
					</p>
				</div>
			</div>
		</div>
	</section>

	<section class="contact-sec" id="contact">
		<div class="contact-container">
			<h2 class="bg-title">connect <br /> with me</h2>
			<div class="overlay">
				<div class="txt-container">
					<div class="logo" />
					<h3 class="title">contact me</h3>
					<p class="txt">
						Lorem ipsum dolor sit amet consectetur adipisicing elit.
						Magni blanditiis laborum rem architecto omnis!
					</p>
					<address class="address">
						<h6 class="addr-txt icon-left phone">
							<a
								href="https://wa.me/+237656766500?text=Hello%20I%20am%20interested%20in%20your%20work"
								>+237 656 766 500</a
							>
						</h6>
						<h6 class="addr-txt icon-left loca">
							Douala, Cameroon
						</h6>
						<h6 class="addr-txt icon-left mail">
							<a href="mailto:gnopaexcel@yahoo.fr"
								>gnopaexcel@yahoo.fr</a
							>
						</h6>
					</address>
				</div>
				<div class="form-container">
					<form
						action="mailto:gnopaexcel@yahoo.fr"
						class="contact-form"
					>
						<input
							type="email"
							name="email"
							id="email"
							placeholder="your email"
							class="in"
						/>
						<input
							type="text"
							name="name"
							id="name"
							placeholder="name"
							class="in"
						/>
						<textarea
							name="message"
							id="message"
							placeholder="message"
							class="in message-in"
						/>
						<input type="submit" value="send" class="submit-btn" />
					</form>
				</div>
			</div>
		</div>
	</section>

	<footer class="footer">
		<div class="footer-container">
			<nav class="footer-navbar">
				<div class="icons-container">
					<div class="logo-container">
						<h2 class="logo-txt">g-e</h2>
					</div>
					<a
							href="https://github.com/ExcelDurant"
							target="_blank"
							class="icon-link"
							><img
								src="./../assets/img/github.svg"
								class="full-img"
								alt=""
							/></a
						>
						<a
							href="https://twitter.com/DurantExcel"
							target="_blank"
							class="icon-link icon-left twitt"
							><img
								src="./../assets/img/twitter.svg"
								class="full-img"
								alt=""
							/></a
						>
						<a
							href="https://www.instagram.com/troptop_ex/"
							target="_blank"
							class="icon-link icon-left insta"
							><img
								src="./../assets/img/instagram.svg"
								class="full-img"
								alt=""
							/></a
						>
						<a
							href="https://www.linkedin.com/in/excel-gnopa-b5a8161b3/"
							target="_blank"
							class="icon-link icon-left linkin"
							><img
								src="./../assets/img/linkedin.svg"
								class="full-img"
								alt=""
							/></a
						>
				</div>
				<!-- svelte-ignore a11y-missing-attribute -->
				<ul class="navlist">
					<!-- svelte-ignore a11y-invalid-attribute -->
					<!-- svelte-ignore a11y-missing-attribute -->
					<li><a on:click={() => animateScroll.scrollTo({element: '#excel'})} class="navlink">excel</a></li>
					<!-- svelte-ignore a11y-invalid-attribute -->
					<li><a on:click={() => animateScroll.scrollTo({element: '#service'})} class="navlink">services</a></li>
					<!-- svelte-ignore a11y-invalid-attribute -->
					<li><a on:click={() => animateScroll.scrollTo({element: '#portfolio'})} class="navlink">portfolio</a></li>
					<!-- svelte-ignore a11y-invalid-attribute -->
					<li><a on:click={() => animateScroll.scrollTo({element: '#tools'})} class="navlink">tools</a></li>
					<!-- svelte-ignore a11y-invalid-attribute -->
					<li><a on:click={() => animateScroll.scrollTo({element: '#contact'})} class="navlink">contact</a></li>
				</ul>
			</nav>
			<div class="seperation" />
			<div class="copyright-container">
				<h3 class="copyright-txt">Copyright 2021 gnopa-excel.com</h3>
			</div>
		</div>
	</footer>
</div>

<style lang="scss">
$headFont: 'Poppins',
sans-serif;
$bodyFont: 'Noto Sans TC',
sans-serif;
$blue      : #1d2cb4;
$lightBlue : #3646E5;
$blueBlack : #5C6086;
$lightGray : #D1D6FF;
$lightWhite: #EFF0FF;
$grayWhite :rgb(196, 196, 196);
$bgTxtColor:rgba(255, 255, 255, 0.068);
$txtColor:rgb(133, 133, 133);
@mixin mqx($width) {
    @media only screen and (max-width:$width) {
        @content;
    }
}

* {
    font-family   : $bodyFont;
}

.full-img {
    width : 100%;
    height: 100%;
}

.logo-txt {
    text-transform: uppercase;
    color: $blue;
    // font-family: cursive;
}

.overlay {
    z-index : 2;
    position: relative;
}

.bg-title {
    z-index : 0;
    position: absolute;
    color   : $bgTxtColor;
}

.title {
    text-transform: capitalize;
}

.header-txt {
    color      : $grayWhite;
    font-weight: 200;
}

.icon-left::before {
    display: inline-block;
    font-style: normal;
    font-variant: normal;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    font-family: "Font Awesome 5 Free"; 
    font-weight: 900;
    color: $lightBlue;
    margin-right: 10px;
}

.header {
    width           : 100%;
    height          : 160px;
    background-color: $blue;
    display         : flex;
    align-items     : center;
    justify-content : center;

    .navbar {
        width          : 70%;
        display        : flex;
        justify-content: space-between;
        font-family    : $headFont;

        .logo-container {
            width           : 50px;
            height          : 50px;
            background-color: white;
            border-radius   : 50%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .navlist {
            display        : flex;
            justify-content: space-between;

            .navlink {
                color       : white;
                padding     : 5px 0;
                margin-right: 25px;
                transition  : 0.5s border;
                color       : $lightWhite;
                font-weight : 300;

                &:hover {
                    text-decoration: underline;
                }
            }
        }
    }

    @include mqx(1000px) {
        .navbar {
            width: 95%;
        }
    }
}

.home-sec {
    width           : 100%;
    min-height      : 500px;
    background-color: $blue;
    color           : white;
    overflow        : hidden;
}

.home-container {
    width          : 80%;
    margin         : 0 auto;
    margin-top     : 80px;
    display        : flex;
    justify-content: space-between;
    align-items    : center;

    i {
        font-size: 20px;
        color    : $grayWhite;
		font-family: "Font Awesome 5 Free"; 
		text-rendering: auto;

        &:hover {
            color: white;
        }
    }

    .txt-container {
        position: relative;

        .title {
            line-height  : 6rem;
            margin-bottom: 45px;
            font-size    : 6rem;
        }

        .txt {
            color        : $grayWhite;
            margin-bottom: 30px;
        }

        .icons-container {
            width          : 150px;
            display        : flex;
            justify-content: space-between;
			.icon-link {
				width:25px;
				height:25px;
				border-radius:50%;
				border:none;
				transition:0.5s margin;
				&:hover {
					margin-top:-2%;
				}
			}
        }


        .bg-title {
            font-size: 11rem;
            color    : rgba(255, 255, 255, 0.068);
            z-index  : 0;
            position : absolute;
            top      : 27%;
        }

    }

    .logo-container {
        min-width       : 400px;
        min-height      : 400px;
        border-radius   : 50%;
        display         : flex;
        align-items     : center;
        justify-content : center;
        background-color: white;
        color: $blue;
        .logo-txt {
            text-transform: uppercase;
            font-size: 10rem;
        }
    }

    @include mqx(900px) {
        width: 98%;
        flex-direction: column;

        .txt-container {
            .title {
                font-size: 4rem;
            }
            .bg-title {
                font-size: 5.7rem;
            }
            .icons-container {
                margin-bottom: 30px;
                align-self: center;
            }
        }
    }

    @include mqx(650px) {
        .txt-container {
            .title {
                line-height: 1.4;
                font-size: 3rem;
            }
        }
        .logo-container {
            min-width: 300px;
            min-height: 300px;
            .logo-txt {
                font-size: 8rem;
            }
        }
    }
}

.excel-sec {
    background-color: $blue;
    color           : white;
    overflow        : hidden;
}

.excel-container {
    width           : 75%;
    margin          : 0 auto;
    display         : flex;
    margin-top      : 100px;
    margin-bottom   : 50px;
    background-color: $lightBlue;
    border-radius   : 100px;
    overflow        : hidden;

    .img-container {
        width     : 30%;
        height    : 100%;
        align-self: flex-end;

        img {
            opacity: 0.3;
            height : 150%;
        }
    }

    .txt-container {
        width   : 65%;
        position: relative;
        padding : 80px;

        .header-txt {
            font-size: 25px;
        }

        .title {
            font-size  : 4rem;
            line-height: 1.2;
        }

        .txt {
            color      : $lightGray;
            font-weight: 100;
            font-size  : 15px;
            line-height: 1.8;
        }

        .bg-title {
            z-index    : 0;
            position   : absolute;
            top        : 5%;
            font-size  : 11rem;
            color      : rgba(255, 255, 255, 0.068);
            line-height: 0.8;
        }
    }

    @include mqx(1280px) {
        .txt-container {
            padding: 40px;
            .title {
                font-size: 3.4rem;
            }
        }
    }

    @include mqx(1000px) {
        width: 95%;
        flex-direction: column;
        justify-content: space-evenly;
        .img-container {
            order: 2;
            width: 60%;
            align-self: center;
            img {
                height: 100%;
            }
        }
        .txt-container {
            width: 100%;
            order: 1;
            text-align: center;
            .bg-title {
                font-size: 9rem;
            }
        }
    }

    @include mqx(650px) {
        .txt-container {
            padding: 40px;
            .header-txt {
                font-size: 1.3rem;
                margin-bottom: 10px;
            }
            .title {
                font-size: 2.2rem;
                line-height: 1;
                margin-bottom: 20px;
            }
            .txt {
                line-height: 1.3;
                font-size: 0.9rem;
            }
            .bg-title {
                font-size: 6rem;
            }
        }
    }
}

.service-sec {
    width                     : 100%;
    background-color          : $blue;
    overflow                  : hidden;
    border-bottom-left-radius : 120px;
    @include mqx(880px) {
        border-bottom-left-radius : 60px;
    }
}

.service-container {
    width     : 65%;
    margin    : 0 auto;
    margin-top: 100px;
    color     : white;

    .txt-container {
        position     : relative;
        margin-bottom: 40px;

        .bg-title {
            position     : relative;
            z-index      : 0;
            margin-bottom: -28px;
            line-height  : 0.8;
            font-size    : 11rem;
            font-weight  : 900;
            z-index      : 0;
            color        : rgba(255, 255, 255, 0.068);
        }

        .logo {
            width        : 40px;
            height       : 40px;
            margin-bottom: 10px;
            border-radius: 50%;
            box-shadow   : 1px 1px 0.1px 10px white;
        }

        .titles {
            width      : 70%;
            display    : flex;
            align-items: center;

            .title {
                font-size   : 48px;
                margin-right: 30px;
            }

            .txt {
                color      : $lightGray;
                font-size  : 14px;
                font-weight: 400;
                line-height: 2;
            }
        }
    }

    .services {
        width          : 100%;
        display        : flex;
        justify-content: space-between;
        margin-bottom  : 100px;

        .service-card {
            display         : inline-block;
            width           : 30%;
            min-width: 250px;
            margin-bottom: 40px;
            background-color: $lightBlue;
            border-radius   : 50px;
            padding         : 30px;

            .card-title {
                font-size    : 25px;
                text-align   : center;
                margin-bottom: 20px;
            }
        }
    }

    @include mqx(1100px) {
        width: 98%;
        .txt-container {
            .titles {
                width: 100%;
                flex-direction: column;
                align-items: flex-start;
            }
        }
    }

    @include mqx(880px) {
        .txt-container {
            .bg-title {
                font-size: 5rem;
            }
        }
        .services {
            flex-direction: column;
            .service-card {
                align-self: center;
            }
        }
    }
}

.portfolio-sec {
    padding-top: 250px;
    margin-bottom: 100px;
}

.portfolio-container {
    width : 70%;
    margin: 0 auto;

    .txt-container {
        margin-bottom: 50px;

        .bg-title {
            top: 0%;
            left: 6%;
            line-height  : 0.8;
            font-size    : 10rem;
            font-weight  : 900;
            z-index      : 0;
            color: rgba(0, 0, 255, 0.075);
        }

        .logo {
            width        : 40px;
            height       : 40px;
            margin-bottom: 10px;
            border-radius: 50%;
            box-shadow   : 1px 1px 0.1px 10px $lightBlue;
        }
        .titles {
            width      : 70%;
            display    : flex;
            align-items: center;

            .title {
                font-size   : 48px;
                margin-right: 30px;
                color: $lightBlue;
            }

            .txt {
                color      : gray;
                font-size  : 14px;
                font-weight: 400;
                line-height: 2;
            }
        }
    }

    .works-grid {
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
        margin-bottom: 30px;

        .work-card {
            width: 300px;
            height: 300px;
            margin-right: 40px;
            margin-bottom: 40px;
            border-radius: 30px;
            box-shadow: 1px 2px 7px 1px rgba(135,135,135,0.75);
            overflow: hidden;
            transition: 1s margin;
            img {
                height: 150%;
                width: 100%;
            }

            &:hover {
                box-shadow: 1px 2px 10px 4px rgba(97, 97, 97, 0.75);
                margin-top: -10%;
            }
        }
    }

    @include mqx(1100px) {
        width: 95%;
        .txt-container {
            .bg-title {
                font-size: 6rem;
                top: 6%;
            }
            .titles {
                width: 100%;
                flex-direction: column;
                align-items: flex-start;
            }
        }
    }
    @include mqx(800px) {
        .txt-container {
            .bg-title {
                font-size: 4.5rem;
            }
        }
        .works-grid {
            .work-card {
                margin: 40px;
            }
        }
    }
}

.tools-sec {
    padding-top: 200px;
    margin-bottom: 10px;
}

.tools-container {
    width: 70%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;

    .icons-container {
        width: 48%;
        display: flex;
        flex-wrap: wrap;

        .icon-container {
            width: 70px;
            height: auto;
            margin: 20px;
        }
    }
    .txt-container {
        width: 48%;

        .bg-title {
            top: 0%;
            line-height  : 0.8;
            font-size    : 11rem;
            font-weight  : 900;
            color: rgba(0, 0, 255, 0.075);
        }

        .logo {
            width        : 40px;
            height       : 40px;
            margin-bottom: 10px;
            border-radius: 50%;
            box-shadow   : 1px 1px 0.1px 10px $lightBlue;
        }

        .title {
            font-size   : 48px;
            margin-right: 30px;
            color: $lightBlue;
        }

        .txt {
            color: $txtColor;
        }
    }

    @include mqx(1100px) {
        width: 95%;
    }

    @include mqx(900px) {
        flex-direction: column;
        align-items: center;
        .txt-container {
            width: 100%;
            order: 1;
            margin-bottom: 20px;
            .bg-title {
                font-size: 8rem;
            }
        }
        .icons-container {
            order: 2;
            width: 100%;
        }
    }
}

.contact-sec {
    padding-top: 300px;
    padding-bottom: 20px;
    margin-bottom: -100px;
    background-color: white;
    z-index: 2;
    border-bottom-left-radius: 120px;
    border-bottom-right-radius: 120px;
    @include mqx(650px) {
        border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
    }
}

.contact-container {
    width: 70%;
    margin: 0 auto;
    .bg-title {
        top: 5%;
        left: 20%;
        letter-spacing: 1.5;
        line-height  : 0.8;
        font-size    : 11rem;
        font-weight  : 900;
        color: rgba(0, 0, 255, 0.075);
    }
    .overlay {
        width: 100%;
        display: flex;
        justify-content: space-evenly;

        .txt-container {
            width: 48%;
            .logo {
                width        : 40px;
                height       : 40px;
                margin-bottom: 10px;
                border-radius: 50%;
                box-shadow   : 1px 1px 0.1px 10px $lightBlue;
            }
            .title {
                font-size   : 2.5rem;
                color: $lightBlue;
            }
            .txt {
                color: $txtColor;
                margin-bottom: 20px;
            }
            address {
                .addr-txt {
                    font-size: 1rem;
                    color: $blueBlack;
                    margin-bottom: 10px;
                }
                .phone {
                    a {
                        color: $blueBlack;
                        &:hover {
                            color: $lightGray;
                        }
                    }
                    &::before {
                        content: '\f095';
                    }
                }
                .loca {
                    &::before {
                        content: '\f21d';
                    }
                }
                .mail {
                    cursor: pointer;
                    a {
                        color: $blueBlack;
                        &:hover {
                            color: $lightGray;
                        }
                    }
                    &::before {
                        content: '\f0e0';
                    }
                }
            }
        }
        .form-container {
            width: 40%;
            min-width: 350px;
            border-radius: 30px;
            box-shadow: 1px 9px 17px -1px rgba(138,138,138,0.75);
            padding: 40px;
            background-color: white;
            margin-bottom: 50px;

            .contact-form {
                width: 100%;
                margin: 0 auto;
                display: flex;
                flex-direction: column;
                justify-content: space-between;

                .in {
                    margin-bottom: 20px;
                    border-radius: 15px;
                    border: none;
                    background-color: rgba(210, 210, 252, 0.425);
                    height: 40px;
                    padding-left: 10px;
                    &:focus {
                        border: 1px solid rgba(210, 210, 252, 0.808);
                    }
                }
                .message-in {
                    height: 100px;
                    padding-top: 10px;
                }
                .submit-btn {
                    width: 50%;
                    padding: 10px 0;
                    align-self: flex-start;
                    background-color: $lightBlue;
                    border-radius: 10px;
                    color: white;
                    font-weight: 900;
                    border: none;
                    cursor: pointer;
                    &:hover {
                        background-color: $blue;
                    }
                }
            }
        }
    }

    @include mqx(1100px) {
        width: 95%;
    }
    @include mqx(900px) {
        .bg-title {
            font-size: 8rem;
            left: 0;
            top: 10%;
        }
        .overlay {
            flex-direction: column;
            align-items: center;
            .txt-container {
                width: 100%;
                margin-bottom: 20px;
            }
        }
    }
    @include mqx(650px) {
        .bg-title {
            font-size: 5rem;
            top: 17%;
        }
    }
}

.footer {
    min-height: 300px;
    background-color: $blue;
}

.footer-container {
    width: 70%;
    margin: 100px auto;
    margin-top: 200px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;

    .footer-navbar {
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 30px;

        .icons-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
            .logo-container {
                width           : 50px;
                height          : 50px;
                background-color: white;
                border-radius   : 50%;
                margin-right: 30px;
                display: flex;
                justify-content: center;
                align-items: center;
            }
            .icon-link {
                margin-right: 15px;
				width:25px;
				height:25px;
				transition: 0.5s margin;

				&:hover {
					margin-top:-5%;
				}
            }
            
        }

        .navlist {
            display: flex;
            justify-content: space-between;
            .navlink {
                margin-right: 15px;
                color: white;
                &:hover {
                    text-decoration: underline;
                }
            }
        }
    }
    .seperation {
        width: 100%;
        border: 1px solid rgba(255, 255, 255, 0.459);
        margin-bottom: 30px;
    }
    .copyright-container {
        .copyright-txt {
            font-size: 17px;
            color: $lightGray;
            font-weight: 200;
        }
    }

    @include mqx(1100px) {
        width: 90%;
    }

    @include mqx(900px) {
        .footer-navbar {
            flex-direction: column;
            .icons-container {
                margin-bottom: 15px;
            }
        }
    }
}

</style>
