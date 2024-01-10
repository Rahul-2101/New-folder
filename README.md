<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parallex | RAHUL YADAV</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div id="wrapper">

        <div class="container">
            <img src="https://static.vecteezy.com/system/resources/previews/008/009/718/large_2x/tropical-resort-hotel-beach-paradise-amazing-nature-coast-shore-summer-vacation-travel-adventure-luxury-holiday-landscape-stunning-ocean-lagoon-blue-sky-palm-trees-relax-idyllic-inspire-beach-photo.jpg" class="background">
            <!-- <img src="foreground.png" class="foreground"> -->
            <h1>ADVENTURE</h1>
        </div>
         
        <section>
            <p>
                <span>Adventure Time !</span>
                Adventure is a term used to describe an exciting, often risky, and sometimes challenging experience or journey. It typically involves exploring new places, taking part in thrilling activities, and encountering the unexpected. Adventures can vary greatly in nature, from outdoor expeditions like hiking or rock climbing, to travel adventures in different countries or cultures, to personal growth experiences such as trying something new or facing fears. Adventure can provide opportunities for personal development, self-discovery, and creating lasting memories. It is a way to break routine, step out of one's comfort zone, and embrace the unknown.
            
               
            </p>

            <div class="bg bg1">
                <h3>BIKING</h3>
            </div>

            <p>
                Biking is a popular outdoor activity and mode of transportation that involves riding a bicycle. It is a versatile activity that can be enjoyed by people of all ages and fitness levels. Biking can be done on various terrains, including roads, trails, and mountains. It offers several benefits, such as improving cardiovascular fitness, strengthening muscles, and enhancing mental well-being.

                Biking can be a solo activity, allowing individuals to enjoy solitude and explore nature at their own pace. It can also be a social activity, with group rides or cycling clubs offering opportunities to connect with other enthusiasts. Biking can be a means of commuting, a recreational hobby, or a competitive sport.
                
                There are different types of biking, including road biking, mountain biking, and BMX biking. Each type has its own set of equipment and techniques. Road biking involves riding on paved roads, often for long distances, while mountain biking is done on off-road trails with rugged terrain. BMX biking is a form of cycling that involves performing tricks and stunts on specially designed tracks.
            </p>

            <div class="bg bg2">
                <h3>PARA GLIDING</h3>
            </div>

            <p>
                Paragliding is an exhilarating adventure sport that involves flying through the air using a paraglider, which is a lightweight, foot-launched aircraft. It is a form of free-flying that allows individuals to experience the sensation of soaring like a bird. 

Paragliders are made up of a fabric wing and a harness that the pilot wears. They rely on wind currents and thermals to stay aloft and maneuver through the air. Paragliding can be done in various terrains, including mountains, hills, and coastal areas.

To paraglide, individuals typically launch themselves from a slope or a high point, either by running or with the help of a tow or winch system. Once in the air, pilots can control their direction and altitude by manipulating the wing's brakes and weight shifting.

Paragliding offers a unique perspective of the surrounding landscape and a sense of freedom. It can be a thrilling and adrenaline-filled experience as pilots glide through the air, feeling the wind beneath their wings. It requires skill, knowledge of weather conditions, and proper training to ensure safety.

Paragliding is considered an extreme sport and should only be undertaken by trained and licensed pilots. It is important to receive proper instruction from certified instructors and to adhere to safety guidelines and regulations. With the right training and precautions, paragliding can be a rewarding and unforgettable adventure.
            </p>

            <div class="bg bg3">
                <h3>SURFING</h3>
            </div>

            <p>
                Surfing is a popular water sport that involves riding waves using a surfboard. It originated in ancient Polynesia and has since gained popularity worldwide. Surfers paddle out into the ocean, wait for suitable waves, and then use their skills to catch and ride them back to shore.

                Surfing requires balance, strength, and agility. Surfers use their bodies and the weight distribution on the board to maneuver and maintain control while riding the waves. The sport can be enjoyed by people of all ages and skill levels, from beginners learning the basics to experienced surfers performing advanced maneuvers.
                
                Surfing can be done in various locations, including beaches with consistent waves, reef breaks, and point breaks. It can be a solitary activity, allowing individuals to connect with nature and enjoy the serenity of the ocean. It can also be a social experience, with surfers gathering at popular breaks, sharing waves, and enjoying the camaraderie of the surfing community.
                
                Apart from being a fun and thrilling activity, surfing offers several health benefits. It provides a full-body workout, improving cardiovascular fitness, core strength, and balance. It also offers mental benefits, such as stress relief and a sense of connection with nature.
                
                Like any adventure sport, surfing carries some risks and requires knowledge of ocean conditions, wave dynamics, and safety precautions. It is important for surfers to be aware of their own abilities, wear appropriate safety gear, and respect the ocean and other surfers.
                
                Overall, surfing is a fantastic way to enjoy the ocean, challenge oneself, and experience the thrill of riding waves. It's a sport that can create lasting memories and a deep appreciation for the beauty and power of the ocean.
            </p>

        </section>

    </div>
    
</body>
</html>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins-bold', sans-serif;
}

@import url('https://fonts.googleapis.com/css?family=Poppins:400,700,900');

#wrapper{
    height: 100vh;
    overflow-x: hidden;
    overflow-y: auto;
    perspective: 10px;
}

.container{
    position: relative;
    display: flex;
    justify-content: center;
    align-content: center;
    height: 100%;
    transform-style: preserve-3d;
    z-index: -1;
} 

.background{
    transform: translateZ(-40px) scale(5.05);
}

.foreground{
    transform: translateZ(-20px) scale(3);
}

.background, .forground{
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: -1;
}

h1{
    position: absolute;
    align-self: center;
    color: white;
    font-size: 8rem;
    top: 5rem;
    letter-spacing: 5px;
    font-weight: 800;
    text-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

section{
    color: white; 
}

p{
    background-color: rgb(45,45,45);
    padding: 5rem ;
    color: white;
    font-size: 1.5rem;
}

p span{
    font-size: 70px;
    display: block;
}

.bg1{
    width: auto;
    height:auto;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSkvwz-L0do6jh9MLaesR9wNAsVpfmioFenbQ&usqp=CAU);
}

.bg2{
    width: auto;
    height:auto;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSeVC-7HYVtenl6BOVqAxXtU2p-49dLv3SLyw&usqp=CAU);
}

.bg3{
    width: auto;
    height:auto;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxBDrMcQ1m_mp5j-vCmG_bu7EORanDWngeiQ&usqp=CAU);
}

.bg{
    position: relative;
    background-size: cover;
    background-attachment: fixed;
    height: 500px;
    width: 100%;
}

h3{
    background-color: white;
    padding: 0.5rem 2.5rem;
    color: black;
    display: inline-block;
    position: absolute;
    transform: translateX(-50%) translateY(-50%);
    top:50%;
    left:50%; 
    font-weight: 600;
    font-size: 3.5rem;
}
