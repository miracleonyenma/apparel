<template>
    <header class="app-header">
        <div class="app-header__wrapper">
            <figure class="app-logo">
                <h1>APPAREL</h1>
            </figure>
            <div class="app-header__search-cont">
                <input class="app-header__search-input" type="search" name="glabal-search" id="global-search"
                    placeholder="Search items, apparels, clothes">
                <button class="app-header__search-btn app-icon">
                    <svg class="" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 415.23 415.23">
                        <g id="Layer_2" data-name="Layer 2">
                            <g id="Layer_1-2" data-name="Layer 1">
                                <rect class="null" width="415.23" height="415.23" />
                                <circle class="cls-2" cx="182.12" cy="182.12" r="84.92" />
                                <line class="cls-2" x1="243.28" y1="243.28" x2="318.03" y2="318.03" />
                            </g>
                        </g>
                    </svg>
                </button>
            </div>
            <div class="app-header__actions-cont">
                <router-link to="/about" class="app-header__cart">
                    <span class="app-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 415.23 415.23">
                            <g id="Layer_2" data-name="Layer 2">
                                <g id="Layer_1-2" data-name="Layer 1">
                                    <rect class="null" width="415.23" height="415.23" />
                                    <path class="cls-2"
                                        d="M52.58,81.92H78.12a10,10,0,0,1,9.49,6.84l51,152.91a10,10,0,0,0,9.49,6.84H318.37a10,10,0,0,0,9.63-7.3l34.27-122.38a10,10,0,0,0-9.63-12.7H175" />
                                    <circle class="cls-2" cx="186.1" cy="303.33" r="29.98" />
                                    <circle class="cls-2" cx="279.07" cy="303.33" r="29.98" />
                                </g>
                            </g>
                        </svg>
                    </span>
                </router-link>
                <div class="app-header__account">
                    <span class="app-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 415.23 415.23">
                            <g id="Layer_2" data-name="Layer 2">
                                <g id="Layer_1-2" data-name="Layer 1">
                                    <circle class="cls-1" cx="207.62" cy="207.62" r="42.96" />
                                    <path class="cls-1"
                                        d="M207.62,358a149.75,149.75,0,0,0,97.24-35.68,114.7,114.7,0,0,0-194.48,0A149.75,149.75,0,0,0,207.62,358Z" />
                                    <path class="cls-1" d="M304.85,322.29a150.36,150.36,0,1,0-194.48,0" />
                                    <rect class="null" width="415.23" height="415.23" />
                                </g>
                            </g>
                        </svg>
                    </span>
                </div>
                <div class="app-header__language">
                    <span>NG</span>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
    import '../assets/css/app-header.css'

    export default {
        name: 'app-header'
    }
</script>

<style lang="css" scoped>
</style>