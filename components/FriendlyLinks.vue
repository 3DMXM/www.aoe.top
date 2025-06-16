<script lang='ts' setup>

const links = [
    {
        name: '沐晴夏阳',
        url: 'https://www.1987619.com',
    },
    {
        name: '深沟主页',
        url: 'https://shyngo.cn/',
    },

];

</script>
<template>
    <div class="friendly-links">
        <h3>友情链接</h3>
        <div class="links">
            <div class="links-list" v-for="link in links" :key="link.name">
                <a :href="link.url" target="_blank">{{ link.name }}</a>
            </div>
            <div class="links-list apply">
                <a href="https://github.com/3DMXM/www.aoe.top/discussions/1" target="_blank"
                    rel="noopener noreferrer">申请友链 + </a>
            </div>
        </div>
    </div>
</template>
<script lang='ts'>

export default {
    name: 'FriendlyLinks',
}
</script>
<style lang='less' scoped>
.friendly-links {
    .links {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;

        .links-list {
            padding-left: 1rem;

            a {
                color: #42b883;
                text-decoration: none;

                &:hover {
                    color: #3e916b;
                }
            }

            &.apply {

                a {
                    color: #47a9bb;

                    &:hover {
                        color: #49808a;
                    }
                }
            }
        }
    }
}
</style>
