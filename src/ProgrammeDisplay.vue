<template>
    <div class="programme-display-container">
        <h2 class="content-title">节目详情</h2>
        <div class="seperator-line"></div>
        <div class="programme-info-container">
            <div class="base-info">
                <div class="poster-container">
                    <div class="visible-container">
                        已上架
                    </div>
                    <div class="poster">
                        照片
                    </div>
                </div>
                <div class="text-info">
                    <div class="name-container">
                        <span class="name">名称</span>
                        <span class="release-date">[2018.10.5]</span>
                        <span class="rate">7.2</span>
                    </div>
                    <div class="seperator-line"></div>
                    <div class="tags-container">

                    </div>
                    <div class="desciption"></div>
                    <div class="persons-container"></div>
                </div>
            </div>
            <div class="programme-other-info"></div>
            <div class="programme-other-posters"></div>
        </div>
    </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.programme-display-container {
    .seperator-line {
        margin-bottom: 0px;
    }
    .programme-info-container {
        padding: 0 0 20px 20px;
        .base-info {
            display: flex;
            .poster-container {
                width: 172px;
                margin-right: 10px;
                .visible-container {
                    height: 44px;
                    line-height: 44px;
                }
                .poster {
                    width: 100%;
                    height: 250px;
                }
            }
            .text-info {
                flex: 1;
                .seperator-line {
                    margin: 0;
                }
                .name-container {
                    display: flex;
                    height: 44px;
                    align-items: center;
                    .name {
                        font-size: 20px;
                        color: #fff;
                    }
                    .release-date {
                        font-size: 16px;
                        color: #6F7480;
                        margin: 0 20px;
                    }
                    .rate {
                        font-size: 24px;
                        color: #fff;
                        background: #D27B25;
                        border-radius: 4px;
                        padding: 0px 5px;
                    }
                }
            }
        }
    }
}
</style>
