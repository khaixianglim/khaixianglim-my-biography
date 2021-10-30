<!-- JS -->
<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    let title = "My Biography";
    let myInfo = {
        title: "Info",
        item1: "Lim Khai Xiang",
        item2: 16,
        item3: "SMJK Chung Ling",
};
    let myHobby = {
        title: "Hobby",
        item1: "Playing the Guitar",
        item2: "Coding",
        item3: "Playing Games",
    };
    let myPersonality = {
        title: "Personality",
        item1: "Cheerful",
        item2: "Playful",
        item3: "Helpful",
    };
    import Footer from '$lib/Footer.svelte';
    let github = "Github repository";
</script>
<!-- HTML -->
<Header {title}></Header>
<Section {...myInfo}></Section>
<Section {...myHobby}></Section>
<Section {...myPersonality}></Section>
<Footer {github}></Footer>