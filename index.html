
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio Helton Rodrigues</title>
    <link rel="stylesheet" href="./css/estilos.css">
    <link rel="icon" type="image/png" href="./img/assets/ico/icone.png" id="favicon">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>

<body>
    <!-- Barra de Navegação -->
    <nav class="navbar">
        <ul>
            <li><a href="#home"><i class="fas fa-home"></i> Principal</a></li>
            <li><a href="#home"><i class="fas fa-user"></i> Sobre</a></li>
            <li><a href="#home"><i class="fas fa-envelope"></i> Contato</a></li>
        </ul>
    </nav>

    <div class="conteudo__geral" id="home">
        <div class="container">
            <div class="container-carrossel">
                <div class="carrossel">
                    <div class="carrossel-item" data-title="Php"><i class="fab fa-php"></i></div>
                    <div class="carrossel-item" data-title="Html5"><i class="fab fa-html5"></i></div>
                    <div class="carrossel-item" data-title="Css3"><i class="fab fa-css3-alt"></i></div>
                    <div class="carrossel-item" data-title="Java"><i class="fab fa-js-square"></i></div>
                    <div class="carrossel-item" data-title="Kotlin"><i class="fas fa-code"></i></div>
                    <div class="carrossel-item" data-title="Bootstrap"><i class="fab fa-bootstrap"></i></div>
                    <div class="carrossel-item" data-title="Portfolio"><i class="fas fa-briefcase"></i></div>
                </div>
            </div>
        </div>
    </div>

    <div class="perfil" id="sobre">
        <div class="sobre-mim">
            <div class="hover-h5">Olá, eu sou o Helton Rodrigues :)</div>
            <div class="p">
                Desenvolvedor Front-end com experiência em desenvolvimento Full Stack Jr., especializado em JavaScript, HTML, CSS, PHP, SQL e Kotlin Jr., além de consumo de APIs REST. Sou apaixonado pela criação de componentes reutilizáveis e possuo sólida experiência em projetos gerenciados por metodologias ágeis. Sou formado em Sistemas de Informação e atualmente estou cursando uma especialização em Kotlin e Java.
            </div>
        </div>
    </div>

    <div class="caixa__icones">
        <div class="underline">Foco e Skills</div><br>
        <a href="#" title="Html5" ><i class="fab fa-html5"></i></a>
        <a href="#" title="CSS3" target="_blank"><i class="fab fa-css3-alt"></i></a>
        <a href="#" title="JavaScript" target="_blank"><i class="fab fa-js-square"></i></a>
        <a href="#" title="PHP" target="_blank"><i class="fab fa-php"></i></a>
        <a href="#" title="Bootstrap" target="_blank"><i class="fab fa-bootstrap"></i></a>
        <a href="#" title="Kotlin" target="_blank"><i class="fas fa-code"></i></a>
        <a href="#" title="GitHub" target="_blank"><i class="fab fa-github"></i></a>
        <a href="#" title="LinkedIn" target="_blank"><i class="fab fa-linkedin"></i></a>
    </div>

    <div class="caixa__icones">
        <div class="underline">Contato</div><br>
        <a href="mailto:helttonr@gmail.com" title="Email" target="_blank"><i class="fas fa-envelope"></i></a>
        <a href="https://wa.me/5512981584731" title="WhatsApp" target="_blank"><i class="fab fa-whatsapp whatsapp-icon"></i></a>
    </div>

    <footer>
        &copy; 2024 Helton Rodrigues. Todos os direitos reservados.
    </footer>

</body>

</html>





<script>
    // script.js
    (function() {
        const normalFavicon = './img/assets/ico/icone.png';
        const pulsanteFavicon = './img/assets/ico/icone2.png';
        const favicon = document.getElementById('favicon');

        let isPulsante = false;

        function toggleFavicon() {
            if (isPulsante) {
                favicon.href = normalFavicon;
            } else {
                favicon.href = pulsanteFavicon;
            }
            isPulsante = !isPulsante;
        }

        setInterval(toggleFavicon, 1000); // Alterna a cada segundo
    })();


    const container = document.querySelector(".container");
    const containercarrossel = container.querySelector(".container-carrossel");
    const carrossel = container.querySelector(".carrossel");
    const carrosselItems = carrossel.querySelectorAll(".carrossel-item");

    let isMouseDown = false;
    let currentMousePos = 0;
    let lastMousePos = 0;
    let lastMoveTo = 0;
    let moveTo = 0;
    let autoRotate = 0.5; // Velocidade de rotação automática em graus por frame

    const createcarrossel = () => {
        const carrosselProps = onResize();
        const length = carrosselItems.length;
        const degress = 360 / length;
        const gap = 20;
        const tz = distanceZ(carrosselProps.w, length, gap);

        const fov = calculateFov(carrosselProps);
        const height = calculateHeight(tz);

        container.style.width = tz * 2 + gap * length + "px";
        container.style.height = height + "px";

        carrosselItems.forEach((item, i) => {
            const degressByItem = degress * i + "deg";
            item.style.setProperty("--rotatey", degressByItem);
            item.style.setProperty("--tz", tz + "px");
        });
    };

    const lerp = (a, b, n) => {
        return n * (a - b) + b;
    };

    const distanceZ = (widthElement, length, gap) => {
        return widthElement / 2 / Math.tan(Math.PI / length) + gap;
    };

    const calculateHeight = (z) => {
        const t = Math.atan((90 * Math.PI) / 180 / 2);
        const height = t * 2 * z;

        return height;
    };

    const calculateFov = (carrosselProps) => {
        const perspective = window
            .getComputedStyle(containercarrossel)
            .perspective.split("px")[0];

        const length =
            Math.sqrt(carrosselProps.w * carrosselProps.w) +
            Math.sqrt(carrosselProps.h * carrosselProps.h);
        const fov = 2 * Math.atan(length / (2 * perspective)) * (180 / Math.PI);
        return fov;
    };

    const getPosX = (x) => {
        currentMousePos = x;

        moveTo = currentMousePos < lastMousePos ? moveTo - 2 : moveTo + 2;

        lastMousePos = currentMousePos;
    };

    const update = () => {
        lastMoveTo = lerp(moveTo, lastMoveTo, 0.05);
        carrossel.style.setProperty("--rotatey", lastMoveTo + "deg");
        moveTo += autoRotate; // Incrementa a rotação automática

        requestAnimationFrame(update);
    };

    const onResize = () => {
        const boundingcarrossel = containercarrossel.getBoundingClientRect();

        const carrosselProps = {
            w: boundingcarrossel.width,
            h: boundingcarrossel.height,
        };

        return carrosselProps;
    };

    const initEvents = () => {
        carrossel.addEventListener("mousedown", () => {
            isMouseDown = true;
            carrossel.style.cursor = "grabbing";
        });
        carrossel.addEventListener("mouseup", () => {
            isMouseDown = false;
            carrossel.style.cursor = "grab";
        });
        container.addEventListener("mouseleave", () => (isMouseDown = false));

        carrossel.addEventListener(
            "mousemove",
            (e) => isMouseDown && getPosX(e.clientX)
        );

        carrossel.addEventListener("touchstart", () => {
            isMouseDown = true;
            carrossel.style.cursor = "grabbing";
        });
        carrossel.addEventListener("touchend", () => {
            isMouseDown = false;
            carrossel.style.cursor = "grab";
        });
        container.addEventListener(
            "touchmove",
            (e) => isMouseDown && getPosX(e.touches[0].clientX)
        );

        window.addEventListener("resize", createcarrossel);

        update();
        createcarrossel();
    };

    initEvents();
</script>