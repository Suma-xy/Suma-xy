### Hi there 👋

<!--
**Suma-xy/Suma-xy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" />
</head>
<body>
<script src="https://unpkg.com/tripetto-runner-foundation"></script>
<script src="https://unpkg.com/tripetto-runner-chat"></script>
<script src="https://unpkg.com/tripetto-services"></script>
<script>
var tripetto = TripettoServices.init({ token: "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjoiaUV0d2dhK2xMcThCWHNOK2NWVldNNW5OZUc4anNhc1FtVUtmMFNNQTNrYz0iLCJkZWZpbml0aW9uIjoiUnR5MXUxZGFXWlJCQnFUam9pVW1HUkhJaU8ycDFpM0xiR2J3TzN4d3d0ST0iLCJ0eXBlIjoiY29sbGVjdCJ9.0ohYjoqCPNw_pJ2e01HXRtl0nyCOaIH7Hp3wXOu2n9Y" });

TripettoChat.run({
    element: document.body,
    definition: tripetto.definition,
    styles: tripetto.styles,
    l10n: tripetto.l10n,
    locale: tripetto.locale,
    translations: tripetto.translations,
    attachments: tripetto.attachments,
    onSubmit: tripetto.onSubmit
});
</script>
</body>
</html>
