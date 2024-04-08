<svg
    width="495"
    height="40"
    viewBox="0 0 495 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg">

    <style>
        .header {
            font: 600 18px Sans-Serif;
            fill: #0366d6;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
        }

        @keyframes fadeInAnimation {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

    </style>

    <g transform="translate(0, 25)">
        <text class="header" data-testid="header">${text}</text>
    </g>
</svg>
