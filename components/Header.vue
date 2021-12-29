<template>
    <div>
        <div class="c-overlay"></div>
        <header class="c-header js-header">
            <div class="l-header">
                <button type="button" id="js-buttonHamburger" aria-controls="global-nav" aria-expanded="false" class="c-ham-button c-hamburger">
                    <span class="c-hamburger__line">
                        <span class="u-visible-hidden">
                            メニューを開閉する
                        </span>
                    </span>
                </button>
                <div class="l-header__content">
                    <div class="c-header-logo">
                        <a href="/" class="c-header-logo__link">
                            <img src="~/assets/images/common/logo.svg" alt="ロゴ：match">
                        </a>
                        <span class="c-header-logo__tag-line">探せる・見つかる・エクセル関数</span>
                    </div>
                    <nav class="c-global-nav js-header-nav" id="global-nav">
                        <ul class="c-global-nav__list">
                            <li class="c-global-nav__item">
                                <a href="" class="c-global-nav__link">TOP</a>
                            </li>
                            <li class="c-global-nav__item">
                                <a href="" class="c-global-nav__link">このサイトについて</a>
                            </li>
                            <li class="c-global-nav__item">
                                <a href="" class="c-global-nav__link">おすすめ書籍</a>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div>
        </header>
    </div>
</template>
