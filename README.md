<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NFC POAP</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="shortcut icon" href="/favicon.png" type="image/x-icon">
</head>

<body>
    <nav>
        <img src="data:image/jpeg;base64,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" alt="Logo">
    </nav>

    <main>
        <div class="box">
            <img src="/start.png" alt="star">

            <h1>NFC POAP
                <A> GENERATOR </A>
            </h1>
            <p>
                Is a service that t0fu.tech provide to the
                POAP community as a way to generate random links
                to deliver mint links though NFC technology.
            </p>
            <div class="drag-Area">
                <img src="/upload.png" alt="uploadicon" href="#">
                <header id="dragText">Drag your file with poap links here</header>
                <h6> TXT file max 5MB </h6>
                <input type="file" id="upload" style="display: none;">
                <label class="upload-button" for="upload">SELECT FILE</label>
            </div>
            <div class="email">
                <p>Enter your email to save your links</p>
                <input type="email" name="email" id="email">
                <button class="getlink" id="btn"> GET LINK </button>
            </div>
        </div>
    </main>

    <footer>

    </footer>
</body>
<script>const dropArea = document.querySelector(".drag-Area");
dragText = dropArea.querySelector("header");
button = dropArea.querySelector("button");
input = dropArea.querySelector("input");


let file;
let emails = [];

input.addEventListener("change", function () {
  file = this.files[0];
  showFile();
});

//user drag file over area//
dropArea.addEventListener("dragover", (event) => {
  event.preventDefault();
  dropArea.classList.add("active");
  dragText.textContent = "Release to Upload";
});

//user leave area without drop the file//
dropArea.addEventListener("dragleave", () => {
  dropArea.classList.remove("active");
  dragText.textContent = "Drag your file with poap links here";
});

//user drop the file on area//
dropArea.addEventListener("drop", (event) => {
  event.preventDefault();
  file = event.dataTransfer.files[0];
  showFile();
});

async function showFile() {
  let fileType = file.type;
  let validExtensions = ["text/plain"];
  if (validExtensions.includes(fileType)) {
    let fileReader = new FileReader();
    let textDecoder = new TextDecoder();
    fileReader.onload = function () {
      let buffer = fileReader.result;
      let text = textDecoder.decode(buffer);
      let lines = text.split('\n').map(line => line.trim());
      uploadFile(lines);
    }
    fileReader.readAsArrayBuffer(file);
  } else {
    alert("Please select a txt file.");
  }
}


async function uploadFile(url) {
  const linksArray = url;
  const linksMap = {
    'e-mail':"email",
    'links': linksArray
  };
  // starting the upload
  // for localhost you can use: http://localhost:5000 after semicolon is port number. 
  let response = await fetch('http://localhost:5000/gerenciador', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(linksMap)
  });


  // upload finished
  if (response.status === 200 || response.status === 201) {
    alert("Uploaded successfully");
  } else {
    alert("Failed to upload");
  }
}


        // example {id:1592304983049, title: 'Deadpool', year: 2015}
        const addEmails = (ev)=>{
          ev.preventDefault();  //to stop the form submitting
          let email = {
              id: Date.now(),
              title: document.getElementById('email').value,
              
          }
          emails.push(email);
         // document.forms[0].reset(); // to clear the form for the next entries
          //document.querySelector('email').reset();

          //for display purposes only
           console.warn('added' , {emails} );
          let pre = document.querySelector('#msg pre');
          pre.textContent = '\n' + JSON.stringify(emails, '\t', 2); 

          //saving to localStorage
          localStorage.setItem('Emails', JSON.stringify(emails) );
      }
      document.addEventListener('DOMContentLoaded', ()=>{
          document.getElementById('btn').addEventListener('click', addEmails);
      });</script>
</body>

</html>
