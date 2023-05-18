function sendMail() {
    var params = {
        from_name: document.getElementById("fullName").value,
        email_id: document.getElementById("email_id").value,
        message: document.getElementById("message").value,
    };

    const serviceID = "service_90av2se";
    const templateID = "template_294vll7";

    emailjs
    .send(serviceID, templateID, params)
    .then((res) => {
        document.getElementById("fullName").value = "";
        document.getElementById("email_id").value = "";
        document.getElementById("message").value = "";
        console.log(res);
        alert("Your message has been sent successfully.");
})
    .catch((err) => console.log(err));
}
