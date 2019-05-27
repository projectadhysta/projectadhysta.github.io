---
layout: product
title: Spesialis Pembuat Lapangan Voli
description: Kami adalah spesialis pembuat lapangan voli
photos: /assets/images/2-lapangan-bola-voli.jpg
img: /assets/images/2-lapangan-bola-voli.jpg
img-alt: Spesialis Pembuat Lapangan Voli
---
<section class="features12 cid-rrbuvjz5nE" id="features12-u">
    <div class="container">
        <h3 class="mbr-section-subtitle pb-3 mbr-fonts-style display-5">
            Kami adalah spesialis pembuat lapangan voli.
        </h3>
        <div class="media-container-row pt-5">
            <div class="block-content align-right">
                <div class="card pl-3 pr-3 pb-5">
                    <div class="mbr-card-img-title">
                        <div class="mbr-crt-title">
                        </div>
                    </div>
                    <div class="card-box">
                        <p class="mbr-text mbr-section-text mbr-fonts-style display-7">
                            Kami adalah spesialis pembuat lapangan voli.
                        </p>
                    </div>
                </div>
                <div class="card pl-3 pr-3">
                    <div class="mbr-card-img-title">
                        <div class="mbr-crt-title">
                        </div>
                    </div>
                    <div class="card-box">
                        <p class="mbr-text mbr-section-text mbr-fonts-style display-7">
                            Kami adalah spesialis pembuat lapangan voli.
                        </p>
                    </div>
                </div>
            </div>
            <div class="mbr-figure m-auto" style="width: 39%;">
                <img src="/assets/images/2-lapangan-bola-voli.jpg" alt="Spesialis Pembuat Lapangan Voli" title="Spesialis Pembuat Lapangan Voli">
            </div>
            <div class="block-content align-left">
                <div class="card pl-3 pr-3 pb-5">
                    <div class="mbr-card-img-title">
                        <div class="mbr-crt-title">
                        </div>
                    </div>
                    <div class="card-box">
                        <p class="mbr-text mbr-section-text mbr-fonts-style display-7">
                            Kami adalah spesialis pembuat lapangan voli.</p>
                    </div>
                </div>
                <div class="card pl-3 pr-3">
                    <div class="mbr-card-img-title">
                        <div class="mbr-crt-title">
                        </div>
                    </div>
                    <div class="card-box">
                        <p class="mbr-text mbr-section-text mbr-fonts-style display-7">
                            Kami adalah spesialis pembuat lapangan voli.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="mbr-gallery mbr-slider-carousel cid-rr5zz839BY" id="gallery3-a">
    <div>
        <div>
            <!-- Filter -->
            <!-- Gallery -->
            <div class="mbr-gallery-row">
                <div class="mbr-gallery-layout-default">
                    <div>
                        <div>
                            {% for item in site.data-gallery-voli %}
                            <div class="mbr-gallery-item mbr-gallery-item--p0" data-video-url="false" data-tags="Awesome">
                                <div href="#lb-gallery3-a" data-slide-to="{{ item.number }}" data-toggle="modal"><img src="{{ item.img-src }}" alt="{{ item.img-alt }}" title="{{ item.img-title }}"><span class="icon-focus"></span></div>
                            </div>
                            {% endfor %}
                        </div>
                    </div>
                    <div class="clearfix"></div>
                </div>
            </div><!-- Lightbox -->
            <div data-app-prevent-settings="" class="mbr-slider modal fade carousel slide" tabindex="-1" data-keyboard="true" data-interval="false" id="lb-gallery3-a">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-body">
                            <div class="carousel-inner">
                                {% for item in site.data-gallery-voli %}
                                <div class="carousel-item {{ item.carousel-active }}"><img src="{{ item.img-src }}" alt="{{ item.img-alt }}" title="{{ item.img-title }}"></div>
                                {% endfor %}
                            </div>
                            <a class="carousel-control carousel-control-prev" role="button" data-slide="prev" href="#lb-gallery3-a"><span class="mbri-left mbr-iconfont" aria-hidden="true"></span><span class="sr-only">Previous</span></a><a class="carousel-control carousel-control-next" role="button" data-slide="next" href="#lb-gallery3-a"><span class="mbri-right mbr-iconfont" aria-hidden="true"></span><span class="sr-only">Next</span></a><a class="close" href="#" role="button" data-dismiss="modal"><span class="sr-only">Close</span></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>