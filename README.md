
<!DOCTYPE html>
<html lang="en">   
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Patrick+Hand&family=Sriracha&family=Itim&display=swap" rel="stylesheet">
<script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script><link rel="stylesheet" href="">

<!-- Made with love by Feeldream -->
<title>Untuk Ciaa</title>
</head>
<style>
  *{margin:0;padding:0;box-sizing:border-box;}
  body{overflow:hidden;display:flex;flex-direction:column;justify-content:center;align-items:center;font-family:"Sriracha",serif;background-color:#000;gap:14px;}
  .pink{color:pink}
  .garismerah{border-bottom:1.5px solid red}
  .overlay{position:fixed;top:0;left:0;width:100%;height:100%;display:flex;justify-content:center;align-items:center;background:rgba(0,0,0,.3);z-index:9999;}
  .cover{color:white;margin-top:-180px;display:flex;flex-direction:column;justify-content:center;align-items:center}
  .cover p{font-size:17px;font-weight:700;}
  .lovein{font-size:50px;display:flex;align-items:center;justify-content:center;transition:all .3s ease;}
  .lovein svg{width:80px;height:80px;fill:#fefefe}
  .awalan{margin-top:20px;width:250px;min-height:25px;padding:12px;font-size:13px;color:white;background:rgba(0,0,0,.5);border:1px solid #fff;border-radius:20px;display:flex;align-items:center;text-align:left}
  .awalan svg{margin-right:15px;width:25px;height:25px;stroke:white}
  .stiker{margin-top:70px;margin-bottom:10px;position:absolute;display:flex;justify-content:center;align-items:center;margin-left:auto;margin-right:auto;transform:scale(0);transition:all .75s ease;z-index:9999;}
  .stiker img{display:none;width:100px;height:100px;box-shadow:0 4px 30px rgba(255,255,255,0.3);backdrop-filter:blur(5px);-webkit-backdrop-filter:blur(5px);background:rgba(255,255,255,0.7);border:1px solid rgba(255,255,255,0.3);border-radius:50%;padding:10px;}
  #main-stiker{display:flex}
  h3.title{font-size:16px;color:white;text-shadow:0px 2px 2px rgba(0,0,0,.5);transition:all .7s ease;}
  .wrapper{margin-top:170px;height:100px;width:150px;background-color:#C93757;position:relative;display:flex;justify-content:center;z-index:0;transition:all .7s ease;}
  .lid{position:absolute;height:100%;width:100%;top:0;left:0;border-right:75px solid transparent;border-bottom:50px solid transparent;border-left:75px solid transparent;transform-origin:top;transition:transform 0.3s ease;}
  .lid.one{border-top:50px solid #ED657C;transform:rotateX(0deg);z-index:3;}
  .lid.two{border-top:50px solid #C9374C;transform:rotateX(0deg);z-index:1;transition-delay:0.1s;}
  .envelope{position:absolute;height:100%;width:100%;top:0;left:0;border-top:50px solid transparent;border-right:75px solid #F0C4CD;border-bottom:50px solid #E5BBC2;border-left:75px solid #F2A4B3;z-index:3;box-shadow:2px 2px 5px rgba(255,255,255,0.3);}
  .envelopemoji{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);font-size:24px;z-index:30;}
  .letter{position:absolute;top:0;width:80%;height:80%;background-color:rgba(0,0,0,.5);backdrop-filter:blur(3px);-webkit-backdrop-filter:blur(3px);border-radius:10px;z-index:1;transition:transform 0.5s ease;}
  .letter p{text-align:center;font-size:12px;margin-top:15px;color:#FFF;}
  .container{position:relative;display:block;width:80%;min-height:100px;max-height:250px;overflow:auto;background-color:rgba(0,0,0,.4);backdrop-filter:blur(3px);-webkit-backdrop-filter:blur(3px);border:1px solid white;border-radius:30px;opacity:0;transform:scale(0);padding:15px 25px;z-index:9999;}
  .container h3{font-size:16px;font-weight:bold;color:#fff;text-align:left;}
  .container p{font-size:16px;color:#fff;text-align:left;}
  .titleC{font-size:17px!important;margin-bottom:14px;font-family:"Itim",cursive;}
  .messageC{font-family:"Itim",cursive;}
  .opamuncul{position:relative;opacity:1;transform:scale(1);transition:all 0.7s ease;}
  .opahidden{opacity:0;transform:scale(0);transition:all 0.7s ease;}
  .hidden,#linkmp3{display:none;}
  .semihidden{transform:scale(0);opacity:0;}
  #bodyblur{opacity:.5;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.5);transition:all 1s ease;}
  #sthisblur{backdrop-filter:blur(3px);-webkit-backdrop-filter:blur(3px);position:absolute;top:0;left:0;right:0;bottom:0;}
  #wallpaper{width:100%;height:100%;transform:scale(2);transition:all 1.3s ease;}
  @keyframes float{0%{transform:translateY(0px) rotate(0deg);}50%{transform:translateY(-20px) rotate(10deg);}100%{transform:translateY(0px) rotate(0deg);}}
  .floating-heart{position:fixed;opacity:0;transform:scale(0);font-size:1.5rem;animation:float 3s ease-in-out infinite;z-index:-1;}  
  b.merah{color:red}
  b.putih{padding-left:5px;padding-right:5px;background:white;border-radius:8px}
#scontainer{z-index:-1;width:80%;margin:20px auto;min-height:650px;margin-top:150px;color:#000}@media screen and (max-width:400px){#scontainer{width:100%;margin:50% auto;min-height:800px}}.swrapper{position:fixed}.box div{position:fixed;width:60px;height:60px;background-color:transparent;border:6px solid rgba(255,182,193,.8);border-radius:50%}.box div:nth-child(1){top:12%;left:42%;animation:animate 10s linear infinite}.box div:nth-child(2){top:70%;left:50%;animation:animate 7s linear infinite}.box div:nth-child(3){top:17%;left:6%;animation:animate 9s linear infinite}.box div:nth-child(4){top:20%;left:60%;animation:animate 10s linear infinite}.box div:nth-child(5){top:67%;left:10%;animation:animate 6s linear infinite}.box div:nth-child(6){top:80%;left:70%;animation:animate 12s linear infinite}.box div:nth-child(7){top:60%;left:80%;animation:animate 15s linear infinite}.box div:nth-child(8){top:32%;left:25%;animation:animate 16s linear infinite}.box div:nth-child(9){top:90%;left:25%;animation:animate 9s linear infinite}.box div:nth-child(10){top:20%;left:80%;animation:animate 5s linear infinite}@keyframes animate{0%{transform:scale(0) translateY(0) rotate(0);opacity:.8}100%{transform:scale(1.3) translateY(-90px) rotate(360deg);opacity:0}}
</style>
<body>
	
  <div class="overlay">
		<div class="cover">
	    <p>This is for <span class="pink">youuuu</span> 🩷</p>
	   <div class="awalan">
	     <svg class='line' fill='none' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><g transform='translate(2.000000, 2.000000)'><path d='M9.27542857,0.714285714 C14.0030476,0.714285714 17.836381,4.54666667 17.836381,9.2752381 C17.836381,14.0038095 14.0030476,17.8361905 9.27542857,17.8361905 C4.54685714,17.8361905 0.71447619,14.0038095 0.71447619,9.2752381 C0.71447619,4.54666667 4.54685714,0.714285714 9.27542857,0.714285714 Z'></path><path d='M17.8989524,16.487619 C18.678,16.487619 19.3094286,17.12 19.3094286,17.8980952 C19.3094286,18.6780952 18.678,19.3095238 17.8989524,19.3095238 C17.1199048,19.3095238 16.4875238,18.6780952 16.4875238,17.8980952 C16.4875238,17.12 17.1199048,16.487619 17.8989524,16.487619 Z'></path></g></svg>
	     <label style="font-size:16px">Untuk Ciaa</label>
	   </div>
	</div>
  </div>
   
  <div id="hearts">
  	<div id="bodyblur">
         <!--- Ganti gambar di sini -->
	     <img src="https://feeldreams.github.io/nightin.jpeg" id="wallpaper"/>
	     <div id="thisblur"></div>
	   </div>
  </div>

  <!-- Ganti Audio di sini -->
  <audio src="https://feeldreams.github.io/audio/melody2.mp3" id="linkmp3"></audio>
  
  <div class="stiker">
    <img id="main-stiker" src="https://htmlku.com/0/panda/pusn.gif" />
    <img id="stikerAlt1" src="https://htmlku.com/0/panda/panah.gif" />
  </div>
                
  <div class="wrapper semihidden" id="wrapper">
    <div class="lid one"></div>
    <div class="lid two"></div>
    <div class="envelope">
    	<div class="envelopemoji">❤️‍🔥</div>
    </div>
    <div class="letter" id="letter">
      <p><b>Alooo Ciaaa... 🫠</b><br>... ... ... ... ... ...<br>... ... ... ... ... ... ...</p>
    </div>
  </div>
  <h3 class="title semihidden">Buka <span style="color:pink">surat</span> ini yaa 🫶</h3>
  
  <div class="container" id="container">
    <p class="titleC"><b>Aloooo <span style="color:pink">Ciaa</span> 🫣🫶</b></p>
    <p class="messageC"></p>
  </div>
  
  <!-- Box elements animation -->
    <div id="scontainer">
        <div class="swrapper">
            <div class="box">
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
            </div>
        </div>
    </div>

<script>
function createHearts() {
            const heartsContainer = document.getElementById('hearts');
            const heartSymbols = ['', '', '', '', ''];

            for (let i = 0; i < 25; i++) {
                const heart = document.createElement('div');
                heart.className = 'floating-heart';
                heart.textContent = heartSymbols[Math.floor(Math.random() * heartSymbols.length)];
                heart.style.left = `${Math.random() * 100}vw`;
                heart.style.top = `${Math.random() * 100}vh`;
                heart.style.animationDelay = `${Math.random() * 3}s`;
                heartsContainer.appendChild(heart);
            }
    }

    //createHearts();
        
    const overlay = document.querySelector('.overlay');
    const cover = document.querySelector('.cover');
    const wrapper = document.getElementById('wrapper');
    const title = document.querySelector('.title');
    const lidOne = document.querySelector('.lid.one');
    const lidTwo = document.querySelector('.lid.two');
    const envelopemoji = document.querySelector('.envelopemoji');
    const letter = document.getElementById('letter');
    const container = document.getElementById('container');
    const titleC = document.querySelector('.titleC');
    const messageC = document.querySelector('.messageC');
    const stiker = document.querySelector('.stiker');
    const mainStiker = document.querySelector('#main-stiker');
    audio = new Audio('' + linkmp3.src);

    let clickCount = 0;

    wrapper.addEventListener('click', () => {
      clickCount++;

      if (clickCount === 1) {
        lidOne.style.transform = 'rotateX(90deg)';
        wallpaper.style="transform: scale(1.5)";
        document.querySelector('.envelopemoji').style = "opacity: 0; transform: translate(-50%, -50%) scale(1.5); transition: all 0.5s ease;";
        lidTwo.style.transform = 'rotateX(180deg)';
        
        setTimeout(function(){
        	letter.style.transform = 'translateY(-30px)';
            wallpaper.style="transform: scale(1.8)";
            
            setTimeout(function(){
	        	wrapper.classList.add('opahidden');
		        title.classList.add('opahidden');
		        wallpaper.style="transform: scale(1.5)";
		        setTimeout(function(){
			        container.classList.remove('hidden');
			        container.classList.add('opamuncul');
			        title.classList.add('hidden');
			        stiker.classList.add('opamuncul');
			        wallpaper.style="transform: scale(1)";
			        wrapper.classList.add('hidden');
			        katanimasi();
		        }, 500);
	        }, 1500);
        }, 300);
      } else if (clickCount === 2) {
        letter.style.transform = 'translateY(-30px)';
        wallpaper.style="transform: scale(1.8)";
      } else if (clickCount === 3) {
        wrapper.classList.add('opahidden');
        title.classList.add('opahidden');
        wallpaper.style="transform: scale(1.5)";
        setTimeout(function(){
	        container.classList.remove('hidden');
	        container.classList.add('opamuncul');
	        title.classList.add('hidden');
	        stiker.classList.add('opamuncul');
	        wallpaper.style="transform: scale(1)";
	        wrapper.classList.add('hidden');
	        katanimasi();
	
	        /*
	        setTimeout(() => {
			    stikerHidden();
			    setTimeout(() => {
				    mainStiker.src = stikerAlt1.src;
			    }, 300);
			}, 1000);
			*/
			
        }, 500);
      }
    });
    
    function stikerHidden(){
    	stiker.style="transform:scale(0);opacity:0;";
        setTimeout(function(){stiker.style="transform:scale(1.1);opacity:1;";}, 300);
    }
    
    vjudul = document.querySelector('.titleC').innerHTML;
    titleC.innerHTML = "";
    vmessage = document.querySelector('.messageC').innerHTML;
    messageC.innerHTML = "";
    function katanimasi(){
		new TypeIt(".titleC", {
	    strings: [vjudul],
	    startDelay: 250,
	    speed: 27,
	    cursor: true,
	    afterComplete: function(){      
	      	//clearInterval(scrollInterval);
	      	titleC.innerHTML = vjudul;
	          setTimeout(() => {katanimasiAlts()}, 300);
	    },}).go();
	}
	
	function katanimasiAlt(){
		new TypeIt(".messageC", {
	    strings: [vmessage],
	    startDelay: 1,
	    speed: 30,
	    cursor: true,
	    afterComplete: function(){      
	      	clearInterval(scrollInterval);
	      	messageC.innerHTML = vmessage;
	          setTimeout(() => {
			    stikerHidden();
			    setTimeout(() => {
				    mainStiker.src = stikerAlt1.src;
			    }, 300);
			  }, 100);
	    },}).go();
	}

    function katanimasiAlts(){
        new TypeIt(".messageC", {
        strings: [
				    "Sebelum tahun 2024 ini berakhir, aku mau bilang makasihhh banget udah jadi part yang paling indah buat aku, Ciaa yang selalu ada buat aku, selalu nemenin hari hari aku, makasi juga udah jadi rumah yang paling nyaman yang pernah aku tempati.",
                    "<br>Terimakasih buat semuanya, dan aku bersyukur banget, di tahun yang melelahkan ini, aku dihadirkan seseorang yang sangat sempurna di mataku 💐", 
				    "<br><b>Intinya aku bersyukur banget bisa ketemu sama Ciaaa!!! ✨</b>",
                    "<br>Kedepannya bareng-bareng terus yaa... Aku gamau kehilangan Ciaa dan semoga di tahun yang akan datang kita bisa terus bahagia ya 🫶",
                    "<br>MAKASIH YA SAYANGKUUU, MANISKUU, DUNIAKU, SEMESTAKUU, PUNYAKUUUU... 🥳",
                    "<br><b id='teksLove' style='background:#fff;border-radius:12px;padding:4px 5px;text-shadow:none;color:red'>LOPYUUUU SAYANGKUU 🫣❤️‍🔥🩷</b>",
				 ],
        startDelay: 1,
        speed: 26,
        cursor: true,
        breakLines: true,
        waitUntilVisible: true,
        afterStep: function(instance) {
            if (instance.is('completed')) {
                setTimeout(function() {
                    instance.next();
                }, 700);
            }
        },
        afterComplete: function(){      
            document.querySelector(".ti-cursor").style.display = "none";
            //document.querySelector(".messageC").innerHTML = "Micin, micin apaa yangg<br>bikinn saltinggg? " + "<br><b>Miciinntaiyoouuu </b><br>Aaaakkk~" + "<br><br><b>Btw,</b>" + "Kamu itu kaya Indomie dicampur Le Mineral tauuuu, Soalnyaaa..." + "Kamuu udah jadii selerakuuu, ditambah adaa manis manisnyaa lagii aawwwhhhh "
            //document.querySelector(".messageC").innerHTML += "<br><br><b id='teksLove' style='background:#fff;border-radius:12px;padding:4px 5px;text-shadow:none;color:red'>I miss uuu</b>";
            //defTeksLove = teksLove.innerHTML;
            //teksLove.innerHTML += " <b>1%</b> " + ambilRandomEmoji;
            //setTimeout(animateteksnim, 100);   
            setTimeout(function() {
                clearInterval(scrollInterval);
            }, 1000);
            setTimeout(() => {
                stikerHidden();
                setTimeout(() => {
                   mainStiker.src = stikerAlt1.src;
                 }, 300);
             }, 100);
        },}).go();
    }

    const loveEmojis = ['', '', '', '', '', ''];
    const ambilRandomEmoji = loveEmojis[Math.floor(Math.random() * loveEmojis.length)];
    //const defTeksLove = teksLove.innerHTML;
    function animateteksnim() {        
        let percent = 10;
        setTimeout(function() {
            const intervalId = setInterval(() => {
                if (percent < 10000) {
                    percent += Math.floor(Math.random() * (100 - 10 + 1)) + 75;
                    const randomEmoji = loveEmojis[Math.floor(Math.random() * loveEmojis.length)];
                    teksLove.innerHTML = `<b>${defTeksLove} ${percent}% ${randomEmoji}</b>`;
                } else {
                    clearInterval(intervalId);
                    
                    percent = 10000;
                    const randomEmoji = loveEmojis[Math.floor(Math.random() * loveEmojis.length)];
                    teksLove.innerHTML = `<b>${defTeksLove} <span style='color:red'>${percent}%</span> ${randomEmoji}</b>`;
                    teksLove.style="background:#fff;border-radius:12px;padding:4px 5px;text-shadow:none;color:red;font-size:18px;transition:all .8s ease";

                    // clearInterval(scrollInterval);
                    
                    setTimeout(() => {
                        stikerHidden();
                        setTimeout(() => {
                            mainStiker.src = stikerAlt1.src;
                        }, 300);
                    }, 100);
                }
            }, 20); // Speed 0-100%
        }, 10); // Delay
    }
    
    document.querySelector(".awalan").onclick = async function() {
        audio.play();

    	overlay.style="opacity:0;transition:all .6s ease";
        cover.style="transform:scale(0);opacity:0;transition:all .6s ease";
        setTimeout(function(){
        	overlay.style.display="none";
            wallpaper.style="transform: scale(1)";
            wrapper.classList.remove('semihidden');
            title.classList.remove('semihidden');
            wrapper.classList.add('opamuncul');
            title.classList.add('opamuncul');
            
            document.querySelectorAll('.floating-heart').forEach(element => {
			    element.style.transform = 'scale(1)';
			    element.style.opacity = '0.5';
			    element.style.transition = 'all 1s ease';
			});
			
        }, 300);
    }
    
    function autoScroll() {container.scrollTop += 10;} const scrollInterval = setInterval(autoScroll, 50); 
</script>
</body>
</html>
