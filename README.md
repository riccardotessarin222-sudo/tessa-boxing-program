# tessa-boxing-program
<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tessa Boxing Program</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{background:#0a0a0a;color:#fff;font-family:'Arial Black',Arial,sans-serif;text-shadow:0 0 5px #c1121f}
.container{max-width:1200px;margin:0 auto;padding:10px}
header{background:linear-gradient(180deg,#1a0000,#0a0a0a);border-bottom:4px solid #c1121f;padding:15px;box-shadow:0 0 20px #ff0040}
.logo{display:flex;align-items:center;gap:15px;cursor:pointer;transition:all .4s}
.logo svg{transition:all .4s}
.logo-testo{display:flex;flex-direction:column;line-height:1;overflow:hidden;max-width:0;transition:max-width .4s}
.logo:hover .logo-testo,.logo.espanso .logo-testo
