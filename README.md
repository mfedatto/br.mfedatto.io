# Quem sou eu?

Sou engenheiro de software experiente, com histórico comprovado na liderança de transformações ágeis e no fornecimento de soluções de software de alta qualidade. Minha experiência reside no preenchimento de lacunas e na promoção de uma cultura de colaboração e inovação. Com paixão por tecnologia e dedicação à melhoria contínua, prospero em ambientes dinâmicos onde posso causar um impacto significativo.

<style>body { overflow-y: scroll;}</style>

## Cases

<!-- Link Swiper's CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
<!-- Demo styles -->
<style>
    .swiper {
        width: 100%;
        height: 100%;
    }

    .swiper-slide {
        text-align: center;
        font-size: 18px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .swiper-slide img {
        display: block;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

</style>
<!-- Swiper -->
<div class="swiper mySwiper">
    <div class="swiper-wrapper">
        {% for post in site.posts %}
        {% if post.categories contains "Cases" %}
            <div class="swiper-slide" style="display: inline-block;">
                <img src="{{ post.thumbnail }}" alt="{{ post.title }}" style="display: inline-block; 3: 120px; height: 150px; border-radius: 8%; width: 150px;float: left; margin-right: 10px;" />
                <h3 style="font-size: 1.2rem; text-align: left; margin: 8px 0 8px 0; padding: 0;"><a href="{{ post.url }}">{{ post.title }}</a></h3>
                <p style="font-size: 14px; text-align: left; line-height: 21px;">
                    {{ post.excerpt }}
                </p>
            </div>
        {% endif %}
        {% endfor %}
    </div>
    <div class="swiper-button-next"></div>
    <div class="swiper-button-prev"></div>
    <div class="swiper-pagination"></div>
</div>
<!-- Swiper -->
<div class="swiper mySwiper">
    <div class="swiper-wrapper">
        <section class="swiper-slide p-4 p-md-5 text-center text-lg-start shadow-1-strong rounded" style="background-image: url(https://mdbcdn.b-cdn.net/img/Photos/Others/background2.webp);">
            <div class="row d-flex justify-content-center">
                <div class="col-md-10">
                <div class="card">
                    <div class="card-body m-3">
                    <div class="row">
                        <div class="col-lg-4 d-flex justify-content-center align-items-center mb-4 mb-lg-0">
                        <img src="https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20%2810%29.webp"
                            class="rounded-circle img-fluid shadow-1" alt="woman avatar" width="200" height="200" />
                        </div>
                        <div class="col-lg-8">
                        <p class="text-muted fw-light mb-4">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Id quam sapiente
                            molestiae numquam quas, voluptates omnis nulla ea odio quia similique
                            corrupti magnam.
                        </p>
                        <p class="fw-bold lead mb-2"><strong>Anna Smith</strong></p>
                        <p class="fw-bold text-muted mb-0">Product manager</p>
                        </div>
                    </div>
                    </div>
                </div>
                </div>
            </div>
        </section>
        <section class="swiper-slide p-4 p-md-5 text-center text-lg-start shadow-1-strong rounded" style="background-image: url(https://mdbcdn.b-cdn.net/img/Photos/Others/background2.webp);">
            <div class="row d-flex justify-content-center">
                <div class="col-md-10">
                <div class="card">
                    <div class="card-body m-3">
                    <div class="row">
                        <div class="col-lg-4 d-flex justify-content-center align-items-center mb-4 mb-lg-0">
                        <img src="https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20%2810%29.webp"
                            class="rounded-circle img-fluid shadow-1" alt="woman avatar" width="200" height="200" />
                        </div>
                        <div class="col-lg-8">
                        <p class="text-muted fw-light mb-4">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Id quam sapiente
                            molestiae numquam quas, voluptates omnis nulla ea odio quia similique
                            corrupti magnam.
                        </p>
                        <p class="fw-bold lead mb-2"><strong>Anna Smith</strong></p>
                        <p class="fw-bold text-muted mb-0">Product manager</p>
                        </div>
                    </div>
                    </div>
                </div>
                </div>
            </div>
        </section>
    </div>
    <div class="swiper-button-next"></div>
    <div class="swiper-button-prev"></div>
    <div class="swiper-pagination"></div>
</div>
<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
<!-- Initialize Swiper -->
<script>
    var swiper = new Swiper(".mySwiper", {
        spaceBetween: 30,
        centeredSlides: true,
        autoplay: {
            delay: 5000,
            disableOnInteraction: false,
        },
        pagination: {
            el: ".swiper-pagination",
            clickable: true,
        },
        navigation: {
            nextEl: ".swiper-button-next",
            prevEl: ".swiper-button-prev",
        },
    });
</script>
