<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body style="background: #000;">
    <h1>Email Sender, 👋</h1>
    <p>
        Bu "repo"da python orqali email pochtaga xabar yuborishingiz mumkin
    </p>
    <div class="row">
        <hr>
        <h5>Dastlab "class"imizdan obyekt yaratib olamiz</h5>
        <code>email = Email(MY_EMAIL, APP_PASSWORD)</code>
    </div>
    <div class="row">
        <hr>
        <h5>Kimningdir pochtasiga oddiygina habar yuborish</h5>
        <code>email.send_text('misol@uchun.uz', <mark style="color: yellow;">'sizning xabaringiz'</mark>)</code>
    </div>
    <div class="row">
        <hr>
        <h5>Kimningdir pochtasiga file ko'rishidagi habar yuborish uchun</h5>
        <code>email.send_file('misol@uchun.uz', <mark>"faylning_joylashuvi"</mark>)</code>
    </div>
    <div class="row">
        <hr>
        <h5>Habarni mavzu bilan yuborish</h5>
        <code>email.send_text('misol@uchun.com', 'text', <mark>subject="Habar Matni")</mark></code>
    </div>
    <div class="row">
        <hr>
        <h5>Gipermatinli(HTML) habar yuborish</h5>
        <code>email.send_text('misol@uchun.com', <mark>'&lth1&gtSalom&lt/h1&gt&ltimg src="https://pictures.com/example.jpg"&gt'</mark>, subject="TEXT - ko'rinishidagi habar", <mark>type_='html'</mark></code>)
    </div>
</body>
</html>
