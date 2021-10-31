<!-- JS -->
<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    let title = "biography";
    let myInfo = {
        title: "Info",
        item1: "🌱 Lim Khai Xiang",
        item2: "🥳 16",
        item3: "🏫 SMJK Chung Ling",
};
    let myHobby = {
        title: "Hobby",
        item1: "🎸 Playing the Guitar",
        item2: "💻 Coding",
        item3: "🎮 Playing Games",
    };
    let myPersonality = {
        title: "Personality",
        item1: "😃 Cheerful",
        item2: "😜 Playful",
        item3: "👌 Helpful",
    };
    import Footer from '$lib/Footer.svelte';
    let github = "Github repository";
</script>
<!-- HTML -->
<Header {title}></Header>
<br/>
<body style="background-color: beige; text-align: center">
    <div>
        <table style="border: 1px solid tomato; width: 80%; margin-left: auto; margin-right: auto">
            <tr>
                <td style="width: 70%"> 
                    <p></p>
                    <Section {...myInfo}></Section> 
                    <hr style="width: 50%; background-color: tomato"/>
                    <Section {...myPersonality}></Section>
                    <p></p>
                </td>
                <td> 
                    <p></p>
                    <img style= "border-radius: 50%; border: 2px solid tomato" src="profile-picture.jpg" alt="profile picture" width="240" height="240"/> 
                    <p></p>
                </td> 
            </tr>
        </table>
    </div>
    <br/>
    <div style="width 80%; color: tomato">
        <h3 style="color: tomato; font-family: 'Consolas'"> " </h3>
        <h5 style="color: tomato; font-family: 'Consolas'"> Declare variables, not wars; </h5> 
        <h5 style="color: tomato; font-family: 'Consolas'"> Execute programs, not people! </h5> 
        <h3 style="color: tomato; font-family: 'Consolas'"> " </h3>
    </div>
    <br/>
    <table style="border: 1px solid tomato; width: 80%; margin-left: auto; margin-right: auto">
        <tr>
            <td style="width: 50%"> 
                <p></p>
                <Section {...myHobby}></Section>
                <hr style="width: 50%; background-color: tomato"/>
                <h3 style="color: tomato; font-family: 'Consolas';"> <b> Games I play </b> </h3>
                <table style="border: 1px solid tomato; width: 80%; margin-left: auto; margin-right: auto">
                    <tr>
                        <td style="background-color: tomato; width: 30%">
                            <p></p>
                            <img style= "border-radius: 50%; border: 2px solid tomato" src="valorant-logo.jpg" alt="Valorant Logo" width="80" height="80"/>
                            <p></p>
                        </td>
                        <td> 
                            <h4 style="color: tomato; font-family:'Consolas'"> <b> VALORANT </b> </h4>
                            <a href="https://playvalorant.com/en-us/"> <p style="color: tomato; font-family: 'Consolas'"> Link </p> </a>
                        </td>
                    </tr>
                    <tr style="border: 1px solid tomato">
                        <td style="background-color: tomato; width: 30%">
                            <p></p>
                            <img style= "border-radius: 50%; border: 2px solid tomato" src="honor-of-kings-logo.png" alt="Honor of Kings logo" width="80" height="80"/>
                            <p></p>
                        </td>
                        <td> 
                            <h4 style="color: tomato; font-family:'Consolas'"> <b> Honor of Kings </b> </h4>
                            <a href="https://pvp.qq.com/"> <p style="color: tomato; font-family: 'Consolas'"> Link </p> </a>
                        </td>
                    </tr>
                </table>
                <p></p>
            </td>
            <td> 
                <p></p>
                <h3 style="color: tomato; font-family: 'Consolas';"> <b> Social </b> </h3>
                <table style="border: 1px solid tomato; width: 80%; margin-left: auto; margin-right: auto">
                    <tr style="border: 1px solid tomato">
                        <td style="background-color: tomato; width: 30%">
                            <p></p>
                            <img style= "border-radius: 50%; border: 2px solid tomato" src="facebook-logo.png" alt="Facebook Logo" width="80" height="80"/>
                            <p></p>
                        </td>
                        <td> 
                            <h4 style="color: tomato; font-family:'Consolas'"> <b> Facebook / Messenger </b> </h4>
                            <h6 style="color: tomato; font-family:'Consolas'"> <b> Khai Xiang Lim </b> </h6>
                            <a href="https://www.facebook.com/richardlim.khaixiang58"> <p style="color: tomato; font-family: 'Consolas'"> Link </p> </a>
                        </td>
                    </tr>
                    <tr>
                        <td style="background-color: tomato; width: 30%">
                            <p></p>
                            <img style= "border-radius: 50%; border: 2px solid tomato" src="ig-logo.png" alt="Instagram logo" width="80" height="80"/>
                            <p></p>
                        </td>
                        <td> 
                            <h4 style="color: tomato; font-family:'Consolas'"> <b> Instagram </b> </h4>
                            <h6 style="color: tomato; font-family:'Consolas'"> <b> Khai Xiang Lim </b> </h6>
                            <a href="https://www.instagram.com/khaixiang_lim/"> <p style="color: tomato; font-family: 'Consolas'"> Link </p> </a>
                        </td>
                    </tr>
                    <tr style="border: 1px solid tomato">
                        <td style="background-color: tomato; width: 30%">
                            <p></p>
                            <img style= "border-radius: 50%; border: 2px solid tomato" src="discord-logo.png" alt="Discord logo" width="80" height="80"/>
                            <p></p>
                        </td>
                        <td> 
                            <h4 style="color: tomato; font-family:'Consolas'"> <b> Discord </b> </h4>
                            <h6 style="color: tomato; font-family:'Consolas'"> <b> Khai Xiang Lim #0850 </b> </h6>
                        </td>
                    </tr>
                </table>
                <p></p>
            </td> 
        </tr>
    </table>
    <br/>
    <footer style="text-align: left">
        <p> <b>Credits</b> | Created on 30 October 2021 by Khai Xiang </p>
        <ul>
            <li> <b>Telebort</b> | <a href="https://www.telebort.com/" style="color: white"> Link </a> ⬅ <i> Learn coding here!</i> </li> 
            <li> <b> Svelte </b> | <a href="https://svelte.dev/" style="color: white"> Link </a> </li>
        </ul>
        <p> <b> Github </b> </p>
        <ul>
            <li> <Footer {github}> </Footer> </li>
            <li> <b> Github Account </b> | <a href="https://github.com/khaixianglim" style="color: white"> Link </a> </li>
        </ul>
    </footer>
</body>
<!-- CSS -->
<style>
    footer{
        font-family: 'Consolas', Courier, monospace;
        background-color: tomato;
        padding: 50px;
        color: white;
        margin: auto;
    }
</style>