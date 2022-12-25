<div align="center">
<img src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" align="center" style="width: 60%"/>
</div>  
<div align="center"><h3>🎯 Hey 👋 I'm Charan Teja , a passionate and aspiring Software Engineer 👨‍🎓 </h3></div>  
<div align="center"><h3> 💻 Available for remote work 👨‍💻 </h3></div>  
<br/>

<h3> &#10687  I'm currently an undergraduate pursuing bachelor's in computer science and engineering 💻🎓</h3>
<h3> &#10687  Fun fact : I pronounce django as d'jango 😅 </h3>  


# 💻Tech Stack
import 'package:flutter/material.dart';

class MyApp extends StatefulWidget {
  const MyApp({Key? key}) : super(key: key);
  @override
  State<MyApp> createState() => _MyAppState();
}

class _MyAppState extends State<MyApp> {
  int count = 0;
  /*@override
  void initState() => super.initState();
  @override
  void dispose() => super.dispose();
  */
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: "My portfolio",
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        backgroundColor: Colors.black,
        appBar: AppBar(
          title: Text('Under Development'),
          centerTitle: true,
          backgroundColor: Colors.blueGrey[900],
        ),
        // floatingActionButton: FloatingActionButton(
        //   backgroundColor: Colors.blueGrey[900],
        //   child: Icon(Icons.add),
        //   onPressed: () {
        //     setState(() {
        //       count++;
        //     });
        //   },
        // ),
        // body: Center(
        //   child: Center(
        //     child: Stack(
        //       children: [
        //         Container(
        //           child: Text(
        //             '$count',
        //             style: TextStyle(fontSize: 60),
        //           ),
        //         ),
        //       ],
        //     ),
        //   ),
        // ),
        body: ListView(
          scrollDirection: Axis.vertical,
          addAutomaticKeepAlives: false,
          children: [
            SizedBox(height: 20),
            Container(
              width: 500,
              height: 500,
              child: Column(
                children: [
                  Text(
                    "Tamanna",
                    style: TextStyle(
                      color: Colors.white,
                      fontSize: 35,
                      fontWeight: FontWeight.bold,
                    ),
                  ),
                  Expanded(child: Image.asset('images/tamanna.jpg')),
                ],
              ),
            ),
            SizedBox(height: 20),
            Container(
              width: 500,
              height: 500,
              child: Column(
                children: [
                  Text(
                    "Rakul Preet Singh",
                    style: TextStyle(
                      color: Colors.white,
                      fontSize: 35,
                      fontWeight: FontWeight.bold,
                    ),
                  ),
                  Expanded(
                    child: Image.asset('images/rakul.jpg'),
                  ),
                ],
              ),
            ),
            SizedBox(height: 20),
            Container(
              width: 500,
              height: 500,
              child: Column(
                children: [
                  Text(
                    "Kajal Agarwal",
                    style: TextStyle(
                      color: Colors.white,
                      fontSize: 35,
                      fontWeight: FontWeight.bold,
                    ),
                  ),
                  Expanded(child: Image.asset('images/kajal.jpg')),
                ],
              ),
            ),
            SizedBox(height: 20),
            Container(
              width: 500,
              height: 500,
              child: Column(
                children: [
                  Text(
                    "Nabha Natesh",
                    style: TextStyle(
                      color: Colors.white,
                      fontSize: 35,
                      fontWeight: FontWeight.bold,
                    ),
                  ),
                  Expanded(
                    child: Image.asset('images/nabha.jpg'),
                  ),
                ],
              ),
            ),
            SizedBox(height: 20),
            Container(
              width: 500,
              height: 500,
              child: Column(
                children: [
                  Text(
                    "Shruti Hassan",
                    style: TextStyle(
                      color: Colors.white,
                      fontSize: 35,
                      fontWeight: FontWeight.bold,
                    ),
                  ),
                  Expanded(child: Image.asset('images/sruthi.jpg')),
                ],
              ),
            ),
            SizedBox(height: 20),
          ],
        ),
        bottomNavigationBar: BottomNavigationBar(
          items: const [
            BottomNavigationBarItem(
                icon: Icon(Icons.home_filled), label: 'Home'),
            BottomNavigationBarItem(icon: Icon(Icons.school), label: 'College'),
            BottomNavigationBarItem(
                icon: Icon(Icons.account_circle), label: 'About'),
          ],
        ),
        drawer: Drawer(
          child: Column(
            children: [
              SizedBox(height: 80),
              CircleAvatar(
                child: Icon(Icons.account_circle, size: 100),
                radius: 50,
              ),
              SizedBox(height: 10),
              Text(
                "User Name",
                style: TextStyle(fontWeight: FontWeight.bold, fontSize: 20),
              ),
              SizedBox(height: 10),
              Row(
                children: [
                  Padding(padding: EdgeInsets.all(30)),
                  Icon(Icons.email),
                  SizedBox(width: 5),
                  Text(
                    "kalyanram@gmail.com",
                    style: TextStyle(fontWeight: FontWeight.bold),
                  )
                ],
              ),
              SizedBox(
                height: 50,
              ),
              Expanded(
                child: Container(
                  height: 1000,
                  width: 500,
                  color: Colors.blueGrey[900],
                  child: IconButton(
                    icon: Container(
                      color: Colors.white,
                      width: 68,
                      height: 25,
                      margin: EdgeInsets.all(3),
                      child: Text(
                        "LogOut",
                        style: TextStyle(
                            fontSize: 20, fontWeight: FontWeight.bold),
                      ),
                    ),
                    alignment: Alignment.bottomCenter,
                    onPressed: () {
                      setState(() {
                        // print("Logged Out");
                      });
                    },
                  ),
                ),
              )
            ],
          ),
          // child: Column(
          //   children: [
          //     Expanded(
          //       child: Image.network(
          //         'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.mwallpapers.com%2Fphotos%2Fcelebrities%2Ftamanna-bhatia%2Ftamanna-bhatia-beautiful-hd-photoshoot-stills-1080p-oxw9ps.jpg&f=1&nofb=1&ipt=480beb64be1c33c35a8dfb27bb74106f0c612ba617dff1f8087487d1c4117fec&ipo=images',
          //         alignment: Alignment.topCenter,
          //       ),
          //     ),
          //     Expanded(
          //       child: Image.network(
          //         'https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2F3.bp.blogspot.com%2F-VVdelID_gko%2FVfhfYQA6j4I%2FAAAAAAAAADg%2FbY0OvFW7m7M%2Fs1600%2FSunny-Leone41326269650.jpg&f=1&nofb=1&ipt=5a719724818975e310ed8faf946bb4a64741d4490d47df45171f4ffd77ac8bd6&ipo=images',
          //         alignment: Alignment.bottomCenter,
          //       ),
          //     ),
          //   ],
          // ),
        ),
      ),
    );
  }
}

## Programming Languages
<a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204676862-a2161717-d4ed-4cf4-83a1-c2fd7828832c.png" alt="C++" width="30" height="40"/> </a>
<a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204680324-358b9ad0-cb23-4565-881b-9c3bc95f8a30.jpg" alt="Java" width="50" height="45"/> </a>
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204677751-f94898f2-3331-49a1-a361-7e1d6a64bfea.png" alt="Python" width="90" height="40"/> </a>

## Database Management
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204678125-b8d6371d-a596-4ee4-a2d5-3c70f2fc4176.jpg" alt="MySQL" width="70" height="50"></a>
<!--
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a>
<a href="https://redis.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> </a>-->
## App Development
<a href="https://dart.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="30" height="30"/> </a> &nbsp;&nbsp;
<a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="30" height="30"/> </a>
<a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="50" height="32"/> </a>
  
## Web Development 
<a href="https://www.w3schools.com/html/" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204679054-aab3c2c1-351d-4e79-9cec-c79bda3ee622.jpg" alt="HTML" width="40" height="50"/> </a>
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204678591-0120a302-b66a-4b84-b878-9c454022d2a7.jpg" alt="CSS" width="40" height="56"/> </a>
<!--<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204679250-bc430103-daa7-4c54-a17b-a7d6d195a551.jpg" alt="JavaScript" width="35" height="50"/> </a>
<a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> 
<a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="33"/> </a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> 
<a href="https://redux.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="40" height="40"/> </a>
<a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a>
<a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a>
## Big Data Analytics 
<a href="https://hadoop.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hadoop/apache_hadoop-icon.svg" alt="hadoop" width="40" height="40"/> </a>
<a href="https://hive.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hive/apache_hive-icon.svg" alt="hive" width="40" height="40"/> </a> -->
<!--## Dev Ops-->
## Cyber Security
<a href="https://www.kali.org/" target="_blank"><img style="margin: 10px" src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Kali-dragon-icon.svg" alt="kali linux" width="60" height="50"/></a>
<a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="50"/></a>

## Familiar With : 
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> &nbsp;&nbsp;
<a href="https://unrealengine.com/" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/206552431-bc0e0413-525e-4ca8-8500-aca0d8daa710.png" alt="unreal" width="40" height="40"/> </a> &nbsp;&nbsp;
<a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a>&nbsp;&nbsp;
<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/97008491/204679661-2d6f1b02-b4ef-43ee-a283-17d7fd400143.jpg" alt="aws" width="60" height="40"/> </a>&nbsp;&nbsp;
<a href="https://www.blockchain.com/" target="_blank"><img style="margin: 10px" src="https://res.cloudinary.com/crunchbase-production/image/upload/v1488050925/bhdemjvkug0k9rjqia9t.png" alt="Blockchain" width="40" height="40" /></a>&nbsp;&nbsp;
<a href="https://www.salesforce.com/in/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/salesforce.png" alt="Salesforce" width="60" height="40" /></a></br></br>
# 👨‍💻 Internships </br>
## <a href="https://www.salesforce.com/in/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/salesforce.png" alt="Salesforce" width="40" height="20" /></a> Salesforce Developer Intern : 
![Screenshot (147)](https://user-images.githubusercontent.com/97008491/203742165-5a1d7cdc-490a-4361-a214-4b5095d16570.png)
</br>
### 🔗 View Certificate of proof : [Salesforce_Developer_Certification](https://smartinternz.com/internships/salesforce_certificates/8d06969939c8f260b8d1db5b900f7653)
</br>
<!--
## <a href="https://www.salesforce.com/in/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/salesforce.png" alt="Salesforce" width="60" height="40" /></a> 
Mapping Tech labs Intern :
### 🔗 View Certificate of proof : [Mapping_tech_certificatioin](https://drive.google.com/file/d/10_1SdwsurpKoeU2GGjcEIQQ1psbnd2Vf/view?usp=sharing)
<a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> </a> 
<a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> 
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a>
<a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a>
<a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/>
  
## Cyber Security
<a href="https://www.kali.org/" target="_blank"><img style="margin: 10px" src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Kali-dragon-icon.svg" alt="kali linux" width="60" height="50"/></a>
<a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="50"/></a>

<a href="https://www.blockchain.com/" target="_blank"><img style="margin: 10px" src="https://res.cloudinary.com/crunchbase-production/image/upload/v1488050925/bhdemjvkug0k9rjqia9t.png" alt="Blockchain" width="40" height="40" /></a>&nbsp;&nbsp;
<a href="https://www.salesforce.com/in/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/salesforce.png" alt="Salesforce" width="60" height="40" /></a>
- 📫 How to reach me **peralacharanteja001@gmail.com**
## Framework
<a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> </a>
<a href="https://laravel.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" alt="laravel" width="40" height="40"/> </a>
<a href="https://rubyonrails.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rails/rails-original-wordmark.svg" alt="rails" width="40" height="40"/> </a>
<a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a>
  

## Testing
<a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a>

## Game Engines
<a href="https://unity.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="unity" width="40" height="40"/> </a> 
<a href="https://unrealengine.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/kenangundogan/fontisto/036b7eca71aab1bef8e6a0518f7329f13ed62f6b/icons/svg/brand/unreal-engine.svg" alt="unreal" width="40" height="40"/> </a> 
<br/>
-->
## 📊GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=charanteja00173&theme=radical&hide_border=false&include_all_commits=false&count_private=false)
![](https://github-readme-streak-stats.herokuapp.com/?user=charanteja00173&theme=radical&hide_border=false)
<br/>
## 🤝Connect With Me
<div align="center">
<a href="https://github.com/charanteja00173" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://instagram.com/charanteja001" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</a>  
</div>  
<br/>
<!--
<div align="left">
<img src="https://komarev.com/ghpvc/?username=charanteja00173&&style=flat-square" align="left" />
</div>
<div align="right">
<a href="https://www.buymeacoffee.com/charanteja00173" target="_blank" style="display: inline-block;">
<img src="https://img.shields.io/badge/Donate-Buy%20Me%20A%20Coffee-orange.svg?style=flat-square&logo=buymeacoffee" align="right"/></a>
</div>
<br>
<br>
-->
<p align="center" ><b> ★[ɪᴅɴꜰꜰᴇᴍ]★ </b></p>

