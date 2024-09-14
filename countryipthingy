if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(successFunction, errorFunction);
} else {
    alert("Geolocation is not supported by this browser.");
}

function successFunction(position) {
    var latitude = position.coords.latitude;
    var longitude = position.coords.longitude;
    // Use these coordinates to find the user's country
}

function errorFunction(error) {
    console.log("Error code: " + error.code + " - " + error.message);
}
