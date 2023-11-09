# TUGAS-UTS-WEB-1

index.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>Rayiden Arfah</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <section>
        <div class="container">
        <div class="profile">
            <img class="rounded-circle profileImage" src="foto.jpeg" alt=""/>
            <h2 class="text-center">Rayiden Arfah</h2>
            <h4 class="text-center">Java Development</h4>
        </div>
    </div>
    </section>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#0099ff" fill-opacity="1" d="M0,128L48,122.7C96,117,192,107,288,138.7C384,171,480,245,576,234.7C672,224,768,128,864,117.3C960,107,1056,181,1152,192C1248,203,1344,149,1392,122.7L1440,96L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>
    

    <section class="biodata">
      <h1 class="text-center">BIODATA</h1>
      <div class="container text-center">
        <div class="row">
          <div class="col">
            Tempat Lahir Cianjur, Tanggal 08 juni 2003.
            Alamat Tinggal, Perum Bumi Citra Lestari, Desa Waluya, Kecamatan Cikarang Utara, Kabupaten Bekasi
          </div>


         <div class="col">
              
  <!-- Button trigger modal Kuliah -->
  <button type="button" class="btn btn-secondary" data-bs-toggle="modal" data-bs-target="#kuliahModal">
    Pendidikan Kuliah
  </button>

  <!-- Modal Kuliah -->
  <div class="modal fade" id="kuliahModal" tabindex="-1" aria-labelledby="kuliahLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="kuliahLabel"><a href="https://www.pelitabangsa.ac.id/" target="_blank">Universitas Pelita Bangsa</a></h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          2022-Sekarang (S1 Teknik Informatika)
        </div>
      </div>
    </div>
  </div>
  <br><br> <!-- Menambahkan line break di sini -->
  <!-- Button trigger modal SMK -->
  <button type="button" class="btn btn-secondary" data-bs-toggle="modal" data-bs-target="#smkModal">
    Pendidikan SMK
  </button>

  <!-- Modal SMK -->
  <div class="modal fade" id="smkModal" tabindex="-1" aria-labelledby="smkLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="smkLabel"><a href="https://data.sekolah-kita.net/sekolah/SMKS%20NIHAYATUL%20AMAL_49212" target="_blank">SMK NIHAYATUL AMAL</a></h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          2018-2021 (Teknik Komputer Jaringan)
        </div>
      </div>
    </div>
  </div>
</div>


          <div class="col">
            Bisa Menggunakan Microsoft office Excel, Word, Power Point, Bisa bahasa Pemograman web
          </div>
        </div>
      </div>
    </section>

      <section class="achievement">
      <div class="container">
        <h1 style="color: white;" class="text-center">RIWAYAT PEKERJAAN</h1>
        <div class="container text-center">
          <div class="row">
            <div class="col-sm-3">
              <div class="card" style="width: 17rem;">
                <div class="card-body">
                  <h5 class="card-title">PT. CPM</h5>
                  <h6 class="card-subtitle mb-2 text-body-secondary">Operator Produksi</h6>
                  <p class="card-text">Mengoperasikan mesin dan peralatan produksi sesuai dengan prosedur dan standar operasional yang ditetapkan.</p>
                  <a href="https://www.citraplastik.com/" class="card-link">Card link</a>
                  <a href="#" class="card-link">Another link</a>
                </div>
          </div>
        </div>
      </div>

    </section>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#0099ff" fill-opacity="1" d="M0,128L48,122.7C96,117,192,107,288,138.7C384,171,480,245,576,234.7C672,224,768,128,864,117.3C960,107,1056,181,1152,192C1248,203,1344,149,1392,122.7L1440,96L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
  </body>
</html>

<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title>Kalkulator</title>
    <link rel="stylesheet" type="text/css" href="./style.css" />
</head>
<body>


<div class="calculator">

    <div class="userInput"><p class="userEntry"></p><p class="finalCalc"></p></div>

    <div class="calcButtons">
    

        <button>+/-</button>
        <button>AC</button>
        <button>DEL</button>
        <button class="operator">*</button>

        <button class="number">1</button>
        <button class="number">2</button>
        <button class="number">3</button>
        <button class="operator">+</button>

        <button class="number">4</button>
        <button class="number">5</button>
        <button class="number">6</button>
        <button class="operator">/</button>
    
        <button class="number">7</button>
        <button class="number">8</button>
        <button class="number">9</button>
        <button class="operator">-</button>

    
        <button class="number">0</button>
        <button class="decimal">.</button>
        <button class="operator">=</button>


    </div>
</div>

<script src="./script.js"></script>

</body>
</html>

script.js

let $buttons = document.querySelectorAll("button");
let ui = document.querySelector(".userEntry");
let finalCalc = document.querySelector(".finalCalc");
let opPressed = false;

let valOne = [];
let valTwo = [];
var operator = [];
let finalAnswer = 0;


[...$buttons].map(x => {
    x.addEventListener("click", function (e) {

        switch (this.innerHTML) {
            case "AC":
                clearDisplay();
                break;
            case "DEL":
                removeNumber();
                break;
            case "+/-":
                makeNegative();
                break;
            case "=":
                makeCalculation();
                break;    
            case "+":
                operator.splice(0, 1, this.innerHTML)
                console.log(operator);

                storeValue();
                break;
            case "*":
                operator.splice(0, 1, this.innerHTML)
                console.log(operator);

                storeValue();
                break;
            case "/":
                operator.splice(0, 1, this.innerHTML)
                console.log(operator);

                storeValue();
                break;
            case "-":
                operator.splice(0, 1, this.innerHTML);
                console.log(operator);
                storeValue();
                break;
            default:
                 if (valOne.length >11) {
                    alert("No more values beyond 8");
                }

                 else {

                    valOne.push(this.innerText);
                    ui.textContent = valOne.join("");
                    console.log(valOne);

                }
                break;
            case ".":
                if (valOne.includes(".")) {
                    alert("You cannot use anymore decimals");
                } else {
                    valOne.push(this.innerText);
                    ui.textContent = valOne.join("");

                }
                break;

        }

    })
})



//function add(a, b) {

//    return a + b;
//}


//function subtract(a, b) {
//    return a - b;
//}

//function divide(a, b){

//    return a / b;
//}

//function multiply(a, b){

//    return a * b;
//}

//function module(a, b) {

//    return a % b;
//}



function clearDisplay() {

    ui.textContent = "";
    finalCalc.textContent = ""
    valOne = [];
    valTwo = [];
    operator = [];
}

function removeNumber(e) {

    valOne.pop();
    ui.textContent = valOne.join("");
}


function makeNegative() {

    if (valOne.length < 1) {
        return false;
    }else if(valOne[0] == "-") {
        valOne.shift()

    } else {
        valOne.unshift("-")

    }
    ui.textContent = valOne.join("");
}

function makeCalculation() {

    if (valTwo.length > 0 && operator.length!==0) {
        //finalAnswer = valTwo.concat(operator, valOne).join("");
        finalAnswer = eval(valTwo + operator + valOne.join(""));
        finalCalc.textContent = "";
        finalCalc.textContent = eval(finalAnswer).toFixed(2);
        ui.textContent = "";
        valTwo = eval(finalAnswer);
        valOne = [];
        //operator = [];

    } else if (operator.length == 0) {

        alert("invalid calculation there is no operator");
        
    }

    else {
        //finalAnswer = valTwo.concat(operator, valOne).join
        finalAnswer = finalAnswer = eval(valTwo + operator + valOne.join(""));

        console.log("final answer");
        console.log(finalAnswer);
        finalCalc.textContent = "";
        ui.textContent = "";
        finalCalc.textContent = eval(finalAnswer).toFixed(2);
        //operator = [];
        valTwo = eval(finalAnswer);
        valOne = [];



    }


 

    
}

function storeValue() {




        if (valOne.length == 0 && valTwo.length==0) {
            return false;
        } else if (valTwo.length > 0) {
            finalCalc.textContent = valTwo + " " + operator;
          

            
        }else if(valTwo.length==0) {
            valTwo.push(valOne.join(""));
            valOne = [];
            ui.textContent = "";
            finalCalc.textContent = "";
            finalCalc.textContent = valTwo + " " + operator

            
    }
        finalCalc.textContent = valTwo + " " + operator;

       
        
}
