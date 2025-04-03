# time
a website that allow you to see time using         
function updateTime() {
            let now = new Date();
            let date = now.toLocaleDateString();
            let time = now.toLocaleTimeString();
            document.getElementById("datetime").innerHTML = date + " - " + time;
        }
