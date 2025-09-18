<!DOCTYPE html>
<html lang="en uk">
    <head>
        <title>FACULTY OF SCIENCE AND TECHNOLOGY MRU</title>
    </head>
    <body style="margin:2;font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;background-color: aqua;">
   <header style="background-color: aliceblue;padding:10px;text-align: center;position: fixed;top: 2px;left: 2px;width: 100%;z-index:900;">
    <h1 style="margin: 2px;font-size:20px;">FACULTY OF SCIENCE AND TECHNOLOGY MRU</h1>
    <nav style="margin-top:10px;">
        <a href="#home"style="margin 10px";color:#fffff;text-decoration:none:font-weight:bold;">HOME</a>
        <a href="#about"style="margin 10px";color:fffff;text-decoration:sans-serif:font-weight:bold">ABOUT US</a>
        <a href="#contact"style="margin 10px";color:fffff;text-decoration:Arial:font-weight:bold">CONTACT</a>
    </nav>
   </header>
   <div style="display:flex;margin-top:90px;">
    <div style="width:200px;background-color: rgb(0, 255, 8);padding-top:18px;min-height:90vh;position: fixed;top:70px;left:0px;border-right:3px solid;">
        <h3 style="color: brown;text-align: center;margin-bottom:30px;">DASHBOARD</h3>
        <a href="#profile"style="display:block;color;padding: 18px;px;text-decoration:none;font-weight:bold;border-bottom:2px solid">MY PROFILE</a>
        <a href="#settings"style="display:block;color;padding: 18px;px;text-decoration:none;font-weight:bold;border-bottom:2px solid">SETTINGS</a>
        <a href="#notifications"style="display:block;color;padding: 18px;px;text-decoration:none;font-weight:bold;border-bottom:2px solid">NOTIFICATIONS</a>
        <a href="resources"style="display:block;color;padding: 18px;text-decoration:none;font-weight:bold:border-bottom:2px solid">RESOURCES</a>
    </div>
    <div style="flex:2;margin-left:200px;padding: 25px;">
        <div style="background: url('https://via.placeholder.com/1000×200.png?text=FACULTY OF SCIENCE AND TECHNOLOGY')no-repeat center;background-size: contain;height:200px;border-radius:12px;margin-bottom:25px;"></div>
        <h2 style="color: cyan;margin-top: 0cm;">STEAD</h2>
        <p style="line: height 1.6em;">The faculty of science and technology at MRU is aimed at making skilled and professional
            technical personnels.It also has diffferent programs that enable students to get what they are already 
            aimed at.
            It also involves physical and practical learning.</p>
            <h2 style="color: gold;text-align: center;">COURSES OFFERED</h2>
            <table style="width:150%;border-collapse: collapse ;margin-top: 25px;text-box-edge: 0 4px 10px;">
                <tr>
                   <th style="border: 2px solid;padding: 15px;background-color: lime;text-align: center;">COURSE CODE</th>
                   <th style="border: 2px solid;padding: 15px;background-color: lime;">COURSE</th> 
                   <th style="border: 2px solid;padding: 15px;background-color: lime;">DURATION</th>
                </tr>
                <tr>
                    <td style="border:2px solid;padding: 15px;text-align: center;">IT 202</td>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">BACHELOR OF INFORMATION TECHNOLOGY</td>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">3 YEARS</td>
                </tr>
                <tr>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">DIT 1101</td>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">DIPLOMA IN INFORMATION TECHNOLOGY</td>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">2 YEARS</td>
                </tr>
                <tr>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">BEICT </td>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">BACHELOR OF EDUCATION IN INFORMATION TECHNOLOGY</td>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">3 YEARS</td>
                </tr>
                <tr>
                    <td style="border: 2px solid;padding: 15px;text-align: center;">BSE  303</td>
                <td style="border: 2px solid;padding: 15px ;text-align: center;">BACHELOR OF SOFTWARE ENGINEERING</td>
                <td style="border: 2px solid;padding: 15px;text-align: center;">4 YEARS</td>
                </tr>
            </table>

      <h2 id="about" style="color:#044700;">ABOUT US</h2>
      <p style="line: height 2px;">
        The IT faculty helps to groom a good model of skilled and proffessional people.This comes after students get practical skills from 
        learning and working with ICT.The world needs more of technology which should come from the IT faculty.
      </p>

      <h2 id="contact" style="color:#002147;">CONTACT</h2>
      <p style="line: height 2px;">
        📍 Muteesa I Royal University, Kampala, Uganda <br>
        📞 +256 700 000 000 <br>
        📧 fst@mru.ac.ug
      </p>
    </div>
  </div>

  <footer style="background-color:#002147; color:rgb(255, 255, 255); text-align:center; padding: 15px; margin: top 15px;">
    &copy; <span id="year"></span> Muteesa I Royal University - Faculty of Science and Technology | All Rights Reserved
  </footer>
  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>
