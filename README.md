<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Care Campus ( to aware from health diseases)</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" media="screen and (max-width: 1170px)" href="css/phone.css">
    <link href="https://fonts.googleapis.com/css?family=Baloo+Bhai|Bree+Serif&amp;display=swap" rel="stylesheet">
</head>
<style>
#navbar {
    flex-direction: column;
}

#navbar ul li a{
    font-size: 1rem;
    padding: 0px 7px;
    padding-bottom: 8px;
}

#home{
    height: 370px; 
    padding: 3px 28px;
}

#home::before{
    height: 480px; 
}

#home p{
    font-size: 13px;
}

#services{
    flex-direction: column;
}

#services .box { 
    padding: 14px;
    margin: 2px 0px; 
    margin-bottom: 20px;
}

#clients{
    flex-wrap: wrap;
}

#clients img{
    width: 66px;
    padding: 6px;
    height: auto;
}

#contact-box form{
    width:80%;
}

.h-primary{
    font-size:26px;
}
.btn{
    font-size: 13px;
    padding: 4px 8px;
}

/* CSS Reset */
*{
    margin: 0;
    padding: 0;
}

html{
    scroll-behavior: smooth;
}

/* CSS Variables */
:root{
    --navbar-height: 59px;
}

/* Navigation Bar */
#navbar{
    display: flex;
    align-items: center;
    position: sticky;
    top: 0px;
}

#navbar::before{
    content: "";
    background-color: black;
    position: absolute;
    top:0px;
    left:0px;
    height: 100%;
    width:100%;
    z-index: -1;
    opacity: ;
}

/* Navigation Bar: Logo and Image */
#logo{
    margin: 10px 34px;
}

#logo img{
    height: 59px;
    margin: 3px 6px;
}


/* Navigation Bar: List Styling */

#navbar ul{
    display: flex;
    font-family: 'Baloo Bhai', cursive;
}

#navbar ul li{ 
    list-style: none;
    font-size: 1.3rem;
}

#navbar ul li a{
    color: white;
    display: block;
    padding: 3px 22px;
    border-radius: 20px;
    text-decoration: none;
}

#navbar ul li a:hover{
    color: black;
    background-color: white;
}

/* Home Section */
#home{
    display: flex;
    flex-direction: column;
    padding:3px 200px;
    height: 550px;
    justify-content: center;
    align-items: center;
}

#home::before{ 
    content: "";
    position: absolute;
    background: url('../bg1.jpg') no-repeat center center/cover;
    height: 642px;
    top:0px;
    left:0px;
    width: 100%;
    z-index: -1;
    opacity:0.89;
}

#home h1{
    color:white;
    text-align: center;
    font-family: 'Bree Serif', serif;
}

#home p{
    color:white;
    text-align: center;
    font-size: 1.5rem;
    font-family: 'Bree Serif', serif;
}
/* Services Section */
#services{
    margin: 34px;
    display: flex;
}
#services .box{ 
    border: 2px solid brown;
    padding: 34px;
    margin: 2px 55px;
    border-radius: 28px;
    background: #f2f2f2;
    margin-bottom: 20px;
}

#services .box img{ 
   height: 160px;
   margin: auto;
   display: block;
}

#services .box p{
    font-family: 'Bree Serif', serif;

} 

/* Clients Section */
#client-section{ 
    
}

#client-section::before{
 content: "";
 position: absolute;
 background: url('../bg.jpg');
 width: 100%;
 height: 100%;
 z-index: -1;
 opacity: 0.3;
}

#clients{
    display: flex;
    justify-content: center;
    align-items: center;
}

#clients img{
    height: 64px;
}


/* Contact Section */
#contact{
    position: relative;
}
#contact::before{
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
    opacity: 0.7;
    background: url('../contact.jpg') no-repeat center center/cover;

}
#contact-box{
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 34px;
}
#contact-box input, 
#contact-box textarea{
    width: 100%;
    padding: 0.5rem;
    border-radius: 9px;
    font-size: 1.1rem;
} 

#contact-box form{
    width: 40%;
}

#contact-box label{
   font-size: 1.3rem;
   font-family: 'Bree Serif', serif;

}


footer{
    background: black;
    color: white;
    padding: 9px 20px;
}

/* Utility Classes */
.h-primary{
    font-family: 'Bree Serif', serif;
    font-size: 3.8rem;
    padding: 12px;
}

.h-secondary{
    font-family: 'Bree Serif', serif;
    font-size: 2.3rem;
    padding: 12px;
}

.btn{
    padding: 6px 20px;
    border: 2px solid white;
    background-color: black;
    color: white;
    margin: 17px;
    font-size: 70px;
    border-radius: 10px;
    cursor:pointer;
}

.center{
    text-align: center;
}






</style>
<body>
    <nav id="navbar">
        <div id="logo">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRW4U_pJnjlkMKnBOg0btXiAg-E_o5gDLb3Rg&usqp=CAU" alt="MyOnlineMeal.com">
        </div>
        <ul>
            <li class="item"><a href="#home">Home</a></li>
            <li class="item"><a href="#services-container">Discover</a></li>
            <li class="item"><a href="#client-section">About</a></li>
            <li class="item"><a href="#contact">Login</a></li>
        </ul>
    </nav>

    <section id="home">
       
           <h1 class="btn">Care Campus</h1>
    </section>

    <section id="services-container">
        <h1 class="h-primary center">Diseases</h1>
        <div id="services">
            
<div class="box">
<a href="https://surajk722.github.io/surajk893/" target="_blank">
                <img src="https://domf5oio6qrcr.cloudfront.net/medialibrary/5999/bf58db0e-a495-4738-bbe6-cdb6cfb167a6.jpg" >
</a>
                <h2 class="h-secondary center">Headache</h2>
                <p class="center">Headaches are a very common condition that most people will experience many times during their lives. The main symptom of a headache is pain in your head or face. There are several types of headaches, and tension headaches are the most common. While most headaches aren’t dangerous, certain types can be a sign of a serious underlying condition.</p>
<details>
<summary>Read more....</summary>
<p><h1><b>Causes<b></h1>Your headache symptoms can help your doctor determine its cause and the appropriate treatment. Most headaches aren't the result of a serious illness, but some may result from a life-threatening condition requiring emergency care.

Headaches are generally classified by cause:

<h2>Primary headaches</h2>
A primary headache is caused by overactivity of or problems with pain-sensitive structures in your head. A primary headache isn't a symptom of an underlying disease.

Chemical activity in your brain, the nerves or blood vessels surrounding your skull, or the muscles of your head and neck (or some combination of these factors) can play a role in primary headaches. Some people may also carry genes that make them more likely to develop such headaches.

The most common primary headaches are:

<h2>Cluster headache</h2>
Migraine
Migraine with aura
Tension headache
Trigeminal autonomic cephalalgia (TAC), such as cluster headache and paroxysmal hemicrania</p>
</details>
            </div>

            <div class="box">
<a href="https://surajnicez398.github.io/dibaties/" >

<img src="https://www.health.com/thmb/A3smgB1Vn2iFjypihKKbwykI3Ac=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/GettyImages-1408610206-0e55ba1e71c747f9b4a4767a79c2e989.jpg" ]>
</a>
                <h2 class="h-secondary center">Diabetes</h2>
                <p class="center">Some people with diabetes develop numbness in the feet or poor blood flow. That can make it difficult to notice blisters, sores and cuts. Undetected and untreated wounds can quickly become infected, leading to complications and sometimes amputation. There are many strategies to protect your from wounds and infection.</p>
<details>
<summary>Read more....</summary>
<p>Diabetes is a chronic hormonal disease, which causes high levels of sugar in the blood. It is a result of either the lack of insulin, a hormone produced by the pancreas, or your body's inability to respond to this hormone. High blood sugar levels caused by lack of this hormone is called type 1 diabetes. It is a genetic condition caused by faulty genes that make this chemical and affects mostly young adults and teenagers. When your blood sugar levels escalate due to the failure of response to this hormone,  it is known as type 2 diabetes. It is a more common type of diabetes and is also known as 'adult onset diabetes'. This condition is triggered  mainly by lifestyle factors like an unhealthy diet, sedentary lifestyle and obesity. Today, type 2 diabetes is one of the most common ‘lifestyle diseases’ among people across the world. This is unfortunate because it can also increase your risk of conditions like heart diseasesand hypertension.

Some of the common symptoms of diabetes are excessive hunger, frequent urination and increased thirst. While type 1 diabetes is difficult to manage, type 2 can be controlled by making simple changes in your daily routine.
1. Autoimmune destruction of beta cells
2. Lack of physical activity
3. Certain drugs 
4. Pancreatic disease or injury</p>
</detail>
            </div>

<div class="box">
<a href="https://surajnicez398.github.io/surajgit/" target="_blank">
<img src="https://sahyadrihospital.com/wp-content/uploads/2021/09/Heart-Attack-Symptoms.jpg">
</a>
                <h2 class="h-secondary center">Heart Attack</h2>
                <p class="center">A heart attack is known as myocardial infarction in the medical fraternity. The word ‘Myo’ means muscle while ‘cardial’ denotes heart. ‘Infarction’, on the other hand, refers to death of tissue caused by insufficient blood supply. The death of tissue may lead to a long-lasting damage of cardiac muscles. Heart attack is a condition which usually occurs when the blood supply to the heart is blocked suddenly due to complete blockage of the artery supplying blood to the cardiac muscles. This causes the heart muscle cells to die. </p>
<details>
<summary>Read more....</summary>
<p>The blockage of artery is often caused by plaque formation (deposition and hardening of fatty substances and cholesterol on the walls of arteries) resulting in coronary heart disease (CHD). If left untreated it can be fatal. The severity of damage to the heart tissues caused by a myocardial infarction or heart attack depends on the longevity of the attack. The earlier you receive medical care, the lesser is the damage.<br>
 <h1>Heart Attack Symptoms:-</h1><br>
 1.Upper body pain<br>
 2.Breaking out in cold sweats<br>
3.Sudden dizziness<br>
4.Irregular heartbeat<br>
5. Stubborn cough and cold<br><br>
<h1>Prevention Of Heart Attack</h1><br>
Modifying your lifestyle and taking up a few healthy habits can go a long way in preventing or reducing your risk of a heart attack. Here are a few small steps that will help for sure:
Eat a healthy, balanced diet (avoid excess fat/ oil/ meat; include more of green veggies, fruits, nuts, fish).
Avoid smoking and excessive alcohol intake.
Keep your blood pressure, blood sugar levels and cholesterol within normal limits.
Exercise regularly. This is extremely necessary to maintain a healthy body weight. Obesity is a major risk factor behind heart attack.
Manage stress by practising meditation, breathing techniques and yoga exercises.
Yearly health check-ups with a physician.
</detail>
            </div>
            
<div class="box">
<a href="https://surajk102938.github.io/YASH/" target="_blank">

                <img src="https://ychef.files.bbci.co.uk/1280x720/p02ldcw8.jpg alt="">
</a>
                <h2 class="h-secondary center">Cancer</h2>
                <p class="center">Cancer refers to any one of a large number of diseases characterized by the development of abnormal cells that divide uncontrollably and have the ability to infiltrate and destroy normal body tissue. Cancer often has the ability to spread throughout your body.
Cancer is the second-leading cause of death in the world. But survival rates are improving for many types of cancer, thanks to improvements in cancer screening, treatment and prevention.</p>

<details>
<summary>Read more....</summary>
<p>Cancer is caused by changes (mutations) to the DNA within cells. The DNA inside a cell is packaged into a large number of individual genes, each of which contains a set of instructions telling the cell what functions to perform, as well as how to grow and divide. Errors in the instructions can cause the cell to stop its normal function and may allow a cell to become cancerous.
Prevention
Doctors have identified several ways to reduce your risk of cancer, such as:

Stop smoking. If you smoke, quit. If you don't smoke, don't start. Smoking is linked to several types of cancer — not just lung cancer. Stopping now will reduce your risk of cancer in the future.
Avoid excessive sun exposure. Harmful ultraviolet (UV) rays from the sun can increase your risk of skin cancer. Limit your sun exposure by staying in the shade, wearing protective clothing or applying sunscreen.
Eat a healthy diet. Choose a diet rich in fruits and vegetables. Select whole grains and lean proteins. Limit your intake of processed meats.
Exercise most days of the week. Regular exercise is linked to a lower risk of cancer. Aim for at least 30 minutes of exercise most days of the week. If you haven't been exercising regularly, start out slowly and work your way up to 30 minutes or longer.
Maintain a healthy weight. Being overweight or obese may increase your risk of cancer. Work to achieve and maintain a healthy weight through a combination of a healthy diet and regular exercise.
Drink alcohol in moderation, if you choose to drink. If you choose to drink alcohol, do so in moderation. For healthy adults, that means up to one drink a day for women and up to two drinks a day for men.
Schedule cancer screening exams. Talk to your doctor about what types of cancer screening exams are best for you based on your risk factors.
Ask your doctor about immunizations. Certain viruses increase your risk of cancer. Immunizations may help prevent those viruses, including hepatitis B, which increases the risk of liver cancer, and human papillomavirus (HPV), which increases the risk of cervical cancer and other cancers. Ask your doctor whether immunization against these viruses is appropriate for you.</p>
</details>
            </div>
        </div>
</section>
    

<section id="client-section">
        <h1 class="h-primary center">visit us</h1>
        <div id="clients">
            <div class="client-item">
<a href="https://www.instagram.com/carecampus_2023/">
                <img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/198px-Instagram_logo_2016.svg.png" width="50"> 
</a>
            </div>
<a href="https://www.facebook.com/">
            <div class="client-item">
                <img height="" src="https://cdn2.downdetector.com/static/uploads/c/300/f0d8e/FB-f-Logo__blue_512.png" width="50">
</a>          
  </div>
          
            <div class="client-item">
<a href="https://twitter.com/?lang=en">
                <img src="https://img.freepik.com/premium-vector/new-twitter-logo-x-2023-twitter-x-logo-vector-download_691560-10809.jpg" >
            </a>
</div>

            <div class="client-item">
<a href="https://in.pinterest.com/search/pins/?q=diseases&rs=typed">
                <img src="https://tse2.mm.bing.net/th?id=OIP.YnzvLdcRTubm3jOrqxrs4gHaHa&pid=Api&P=0&h=180">
        </a>    
        </div>

    </section><br><br><br><br><br><br>



    <section id="contact">
        <h3 class="h-primary center">Login/Signup</h3>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">Name: </label>
                    <input type="text" name="name" id="name" placeholder="Enter your name">
                </div>
                <div class="form-group">
                    <label for="email">Email: </label>
                    <input type="email" name="name" id="email" placeholder="Enter your email">
                </div>
                <div class="form-group">
                    <label for="phone">Enter your phone number:</label>
<input type="tel" id="phone" name="phone"placeholder="Enter your phone no." >
                </div>
 <div class="form-group">
                    <label for="password">Password </label>
                    <input type="password" name="name" id="password" placeholder="Enter your password">
                </div><br><br>
 <div class="form-group">
                    <input type="submit" id="Submit">
                </div>
            </form>
        </div>
    </section>

    <footer>
        
    </footer>
