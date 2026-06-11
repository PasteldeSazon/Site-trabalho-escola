**@**charset "UTF-8";

/\*!

&#x20;\* Bootstrap v5.3.0 (https://getbootstrap.com/)

&#x20;\* Copyright 2011-2023 Os Autores do Bootstrap

&#x20;\* Licenciado pelo MIT (https://github.com/twbs/bootstrap/blob/main/LICENSE)

&#x20;\*/

:raiz,

\[data-bs-theme=light] {

&#x20; --bs-azul: #0d6efd;

&#x20; --bs-indigo: #6610f2;

&#x20; --bs-roxo: #6f42c1;

&#x20; --bs-rosa: #d63384;

&#x20; --bs-vermelho: #dc3545;

&#x20; --bs-laranja: #fd7e14;

&#x20; --bs-amarelo: #ffc107;

&#x20; --bs-verde: #198754;

&#x20; --bs-teal: #20c997;

&#x20; --bs-ciano: #0dcaf0;

&#x20; --bs-preto: #000;

&#x20; --bs-white: #fff;

&#x20; --bs-cinza: #6c757d;

&#x20; --bs-gray-dark: #343a40;

&#x20; --bs-gray-100: #f8f9fa;

&#x20; --bs-gray-200: #e9ecef;

&#x20; --bs-gray-300: #dee2e6;

&#x20; --bs-gray-400: #ced4da;

&#x20; --bs-gray-500: #adb5bd;

&#x20; --bs-gray-600: #6c757d;

&#x20; --bs-gray-700: #495057;

&#x20; --bs-gray-800: #343a40;

&#x20; --bs-gray-900: #212529;

&#x20; --bs-primary: #0d6efd;

&#x20; --bs-secundário: #6c757d;

&#x20; --bs-sucesso: #198754;

&#x20; --bs-info: #0dcaf0;

&#x20; --bs-warning: #ffc107;

&#x20; --bs-perigo: #dc3545;

&#x20; --bs-light: #f8f9fa;

&#x20; --bs-dark: #212529;

&#x20; --bs-primary-rgb: 13, 110, 253;

&#x20; --bs-secondary-rgb: 108, 117, 125;

&#x20; --bs-success-rgb: 25, 135, 84;

&#x20; --bs-info-rgb: 13, 202, 240;

&#x20; --bs-warning-rgb: 255, 193, 7;

&#x20; --bs-danger-rgb: 220, 53, 69;

&#x20; --bs-light-rgb: 248, 249, 250;

&#x20; --bs-dark-rgb: 33, 37, 41;

&#x20; --bs-primary-text-emphasis: #052c65;

&#x20; --bs-secondary-text-emphasis: #2b2f32;

&#x20; --bs-success-text-emphasis: #0a3622;

&#x20; --bs-info-text-emphasis: #055160;

&#x20; --bs-warning-text-emphasis: #664d03;

&#x20; --bs-danger-text-emphasis: #58151c;

&#x20; --bs-light-text-emphasis: #495057;

&#x20; --bs-dark-text-emphasis: #495057;

&#x20; --bs-primary-bg-subtle: #cfe2ff;

&#x20; --bs-secondary-bg-subtle: #e2e3e5;

&#x20; --bs-success-bg-subtle: #d1e7dd;

&#x20; --bs-info-bg-subtle: #cff4fc;

&#x20; --bs-warning-bg-subtle: #fff3cd;

&#x20; --bs-danger-bg-subtle: #f8d7da;

&#x20; --bs-light-bg-subtle: #fcfcfd;

&#x20; --bs-dark-bg-subtle: #ced4da;

&#x20; --bs-primary-border-subtle: #9ec5fe;

&#x20; --bs-secondary-border-subtle: #c4c8cb;

&#x20; --bs-success-border-subtle: #a3cfbb;

&#x20; --bs-info-border-subtle: #9eeaf9;

&#x20; --bs-warning-border-subtle: #ffe69c;

&#x20; --bs-danger-border-subtle: #f1aeb5;

&#x20; --bs-light-border-subtle: #e9ecef;

&#x20; --bs-dark-border-subtle: #adb5bd;

&#x20; --bs-white-rgb: 255, 255, 255;

&#x20; --bs-black-rgb: 0, 0, 0;

&#x20; --bs-font-sans-serif: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", "Noto Sans", "Liberation Sans", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";

&#x20; --bs-font-monospace: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;

&#x20; --bs-gradient: gradiente-linear(180deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0));

&#x20; --bs-body-font-family: var(--bs-font-sans-serif);

&#x20; --bs-body-font-size: 1rem;

&#x20; --bs-body-font-weight: 400;

&#x20; --bs-body-line-height: 1.5;

&#x20; --bs-body-color: #212529;

&#x20; --bs-body-color-rgb: 33, 37, 41;

&#x20; --bs-body-bg: #fff;

&#x20; --bs-body-bg-rgb: 255, 255, 255;

&#x20; --bs-emphasis-color: #000;

&#x20; --bs-emphasis-color-rgb: 0, 0, 0;

&#x20; --bs-secondary-color: rgba(33, 37, 41, 0.75);

&#x20; --bs-secondary-color-rgb: 33, 37, 41;

&#x20; --bs-secondary-bg: #e9ecef;

&#x20; --bs-secondary-bg-rgb: 233, 236, 239;

&#x20; --bs-tertiary-color: rgba(33, 37, 41, 0.5);

&#x20; --bs-tertiary-color-rgb: 33, 37, 41;

&#x20; --bs-tertiary-bg: #f8f9fa;

&#x20; --bs-tertiary-bg-rgb: 248, 249, 250;

&#x20; --bs-heading-color: herdar;

&#x20; --bs-link-color: #0d6efd;

&#x20; --bs-link-color-rgb: 13, 110, 253;

&#x20; --bs-link-decoration: sublinhado;

&#x20; --bs-link-hover-color: #0a58ca;

&#x20; --bs-link-hover-color-rgb: 10, 88, 202;

&#x20; --bs-code-color: #d63384;

&#x20; --bs-highlight-bg: #fff3cd;

&#x20; --bs-border-width: 1px;

&#x20; --bs-border-style: solid;

&#x20; --bs-border-color: #dee2e6;

&#x20; --bs-border-color-translucent: rgba(0, 0, 0, 0.175);

&#x20; --bs-border-radius: 0.375rem;

&#x20; --bs-border-radius-sm: 0.25rem;

&#x20; --bs-border-radius-lg: 0.5rem;

&#x20; --bs-border-radius-xl: 1rem;

&#x20; --bs-border-radius-xxl: 2rem;

&#x20; --bs-border-radius-2xl: var(--bs-border-radius-xxl);

&#x20; --bs-border-radius-pill: 50rem;

&#x20; --bs-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);

&#x20; --bs-box-shadow-sm: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);

&#x20; --bs-box-shadow-lg: 0 1rem 3rem rgba(0, 0, 0, 0.175);

&#x20; --bs-box-shadow-inset: inset 0 1px 2px rgba(0, 0, 0, 0.075);

&#x20; --bs-focus-ring-width: 0.25rem;

&#x20; --bs-focus-ring-opacity: 0.25;

&#x20; --bs-focus-ring-color: rgba(13, 110, 253, 0.25);

&#x20; --bs-form-valid-color: #198754;

&#x20; --bs-form-valid-border-color: #198754;

&#x20; --bs-form-invalid-color: #dc3545;

&#x20; --bs-form-invalid-border-color: #dc3545;

}



\[data-bs-theme=dark] {

&#x20; esquema de cores: escuro;

&#x20; --bs-body-color: #adb5bd;

&#x20; --bs-body-color-rgb: 173, 181, 189;

&#x20; --bs-body-bg: #212529;

&#x20; --bs-body-bg-rgb: 33, 37, 41;

&#x20; --bs-emphasis-color: #fff;

&#x20; --bs-emphasis-color-rgb: 255, 255, 255;

&#x20; --bs-secondary-color: rgba(173, 181, 189, 0.75);

&#x20; --bs-secondary-color-rgb: 173, 181, 189;

&#x20; --bs-secondary-bg: #343a40;

&#x20; --bs-secondary-bg-rgb: 52, 58, 64;

&#x20; --bs-tertiary-color: rgba(173, 181, 189, 0.5);

&#x20; --bs-tertiary-color-rgb: 173, 181, 189;

&#x20; --bs-tertiary-bg: #2b3035;

&#x20; --bs-tertiary-bg-rgb: 43, 48, 53;

&#x20; --bs-primary-text-emphasis: #6ea8fe;

&#x20; --bs-secondary-text-emphasis: #a7acb1;

&#x20; --bs-success-text-emphasis: #75b798;

&#x20; --bs-info-text-emphasis: #6edff6;

&#x20; --bs-warning-text-emphasis: #ffda6a;

&#x20; --bs-danger-text-emphasis: #ea868f;

&#x20; --bs-light-text-emphasis: #f8f9fa;

&#x20; --bs-dark-text-emphasis: #dee2e6;

&#x20; --bs-primary-bg-subtle: #031633;

&#x20; --bs-secondary-bg-subtle: #161719;

&#x20; --bs-success-bg-subtle: #051b11;

&#x20; --bs-info-bg-subtle: #032830;

&#x20; --bs-warning-bg-subtle: #332701;

&#x20; --bs-danger-bg-subtle: #2c0b0e;

&#x20; --bs-light-bg-subtle: #343a40;

&#x20; --bs-dark-bg-subtle: #1a1d20;

&#x20; --bs-primary-border-subtle: #084298;

&#x20; --bs-secondary-border-subtle: #41464b;

&#x20; --bs-success-border-subtle: #0f5132;

&#x20; --bs-info-border-subtle: #087990;

&#x20; --bs-warning-border-subtle: #997404;

&#x20; --bs-danger-border-subtle: #842029;

&#x20; --bs-light-border-subtle: #495057;

&#x20; --bs-dark-border-subtle: #343a40;

&#x20; --bs-heading-color: herdar;

&#x20; --bs-link-color: #6ea8fe;

&#x20; --bs-link-hover-color: #8bb9fe;

&#x20; --bs-link-color-rgb: 110, 168, 254;

&#x20; --bs-link-hover-color-rgb: 139, 185, 254;

&#x20; --bs-code-color: #e685b5;

&#x20; --bs-border-color: #495057;

&#x20; --bs-border-color-translucent: rgba(255, 255, 255, 0.15);

&#x20; --bs-form-valid-color: #75b798;

&#x20; --bs-form-valid-border-color: #75b798;

&#x20; --bs-form-invalid-color: #ea868f;

&#x20; --bs-form-invalid-border-color: #ea868f;

}



\*,

\*::antes,

\*::depois {

&#x20; box-sized: caixa com borda;

}



@media (prefers-reduced-motion: no-preference) {

&#x20; :raiz {

&#x20;   Comportamento de rolagem: suave;

&#x20; }

}



corpo {

&#x20; margem: 0;

&#x20; família-fonte: var(--bs-body-font-family);

&#x20; tamanho-da-fonte: var(--bs-body-font-size);

&#x20; peso-da-fonte: var(--bs-body-font-weight);

&#x20; altura-da-linha: var(--bs-body-line-height);

&#x20; cor: var(--bs-body-color);

&#x20; alinhamento de texto: var(--bs-body-text-align);

&#x20; cor de fundo: var(--bs-body-bg);

&#x20; -webkit-text-size-adjust: 100%;

&#x20; -webkit-tap-highlight-color: rgba(0, 0, 0, 0);

}



hora {

&#x20; margem: 1rem 0;

&#x20; cor: herdar;

&#x20; borda: 0;

&#x20; borda superior: var(--bs-border-width) sólido;

&#x20; opacidade: 0,25;

}



h6, .h6, h5, .h5, h4, .h4, h3, .h3, h2, .h2, h1, .h1 {

&#x20; margem superior: 0;

&#x20; margem-inferior: 0,5rem;

&#x20; peso da fonte: 500;

&#x20; altura da linha: 1,2;

&#x20; cor: var(--bs-heading-color);

}



h1, .h1 {

&#x20; tamanho-da-fonte: calc(1,375rem + 1,5vw);

}

@media (min-width: 1200px) {

&#x20; h1, .h1 {

&#x20;   tamanho da fonte: 2,5rem;

&#x20; }

}



h2, .h2 {

&#x20; tamanho-da-fonte: calc(1,325rem + 0,9vw);

}

@media (min-width: 1200px) {

&#x20; h2, .h2 {

&#x20;   tamanho da fonte: 2rem;

&#x20; }

}



h3, .h3 {

&#x20; tamanho-da-fonte: calc(1.3rem + 0.6vw);

}

@media (min-width: 1200px) {

&#x20; h3, .h3 {

&#x20;   tamanho da fonte: 1,75rem;

&#x20; }

}



h4, .h4 {

&#x20; tamanho-da-fonte: calc(1,275rem + 0,3vw);

}

@media (min-width: 1200px) {

&#x20; h4, .h4 {

&#x20;   tamanho da fonte: 1,5rem;

&#x20; }

}



h5, .h5 {

&#x20; tamanho da fonte: 1,25rem;

}



h6, .h6 {

&#x20; tamanho da fonte: 1rem;

}



p {

&#x20; margem superior: 0;

&#x20; margem-inferior: 1rem;

}



abreviatura\[título] {

&#x20; -webkit-text-decoration: sublinhado pontilhado;

&#x20; text-decoration: underline doted;

&#x20; cursor: ajuda;

&#x20; -webkit-text-decoration-skip-ink: nenhum;

&#x20; text-decoration-skip-ink: none;

}



endereço {

&#x20; margem-inferior: 1rem;

&#x20; estilo-da-fonte: normal;

&#x20; altura-da-linha: herdar;

}



ol,

ul {

&#x20; preenchimento-esquerdo: 2rem;

}



ol,

ul,

dl {

&#x20; margem superior: 0;

&#x20; margem-inferior: 1rem;

}



ol ol,

ul ul,

ol ul,

ul ol {

&#x20; margem-inferior: 0;

}



dt {

&#x20; peso da fonte: 700;

}



dd {

&#x20; margem-inferior: 0,5rem;

&#x20; margem-esquerda: 0;

}



bloco de citação {

&#x20; margem: 0 0 1rem;

}



b,

forte {

&#x20; peso da fonte: negrito;

}



pequeno, .pequeno {

&#x20; tamanho da fonte: 0,875em;

}



marca, .marca {

&#x20; preenchimento: 0,1875em;

&#x20; cor de fundo: var(--bs-highlight-bg);

}



sub,

e aí {

&#x20; posição: relativa;

&#x20; tamanho da fonte: 0,75em;

&#x20; altura-da-linha: 0;

&#x20; alinhamento vertical: linha de base;

}



sub {

&#x20; parte inferior: -0,25em;

}



e aí {

&#x20; topo: -0,5em;

}



um {

&#x20; cor: rgba(var(--bs-link-color-rgb), var(--bs-link-opacity, 1));

&#x20; decoração de texto: sublinhado;

}

a:hover {

&#x20; --bs-link-color-rgb: var(--bs-link-hover-color-rgb);

}



a:not(\[href]):not(\[class]), a:not(\[href]):not(\[class]):hover {

&#x20; cor: herdar;

&#x20; decoração de texto: nenhuma;

}



pré,

código,

kbd,

samp {

&#x20; família-fonte: var(--bs-font-monospace);

&#x20; tamanho da fonte: 1em;

}



pré {

&#x20; exibir: bloco;

&#x20; margem superior: 0;

&#x20; margem-inferior: 1rem;

&#x20; estouro: automático;

&#x20; tamanho da fonte: 0,875em;

}

pré-código {

&#x20; tamanho-da-fonte: herdar;

&#x20; cor: herdar;

&#x20; quebra de palavra: normal;

}



código {

&#x20; tamanho da fonte: 0,875em;

&#x20; cor: var(--bs-code-color);

&#x20; quebra-de-palavra: quebra-de-palavra;

}

um > código {

&#x20; cor: herdar;

}



kbd {

&#x20; preenchimento: 0,1875rem 0,375rem;

&#x20; tamanho da fonte: 0,875em;

&#x20; cor: var(--bs-body-bg);

&#x20; cor de fundo: var(--bs-body-color);

&#x20; raio-da-borda: 0,25rem;

}

kbd kbd {

&#x20; preenchimento: 0;

&#x20; tamanho da fonte: 1em;

}



figura {

&#x20; margem: 0 0 1rem;

}



imagem,

svg {

&#x20; alinhamento vertical: meio;

}



mesa {

&#x20; legenda-lado: inferior;

&#x20; colapso de fronteira: colapso;

}



legenda {

&#x20; padding-top: 0.5rem;

&#x20; padding-bottom: 0.5rem;

&#x20; cor: var(--bs-cor-secundária);

&#x20; alinhamento de texto: esquerda;

}



th {

&#x20; alinhamento de texto: herdar;

&#x20; alinhamento de texto: -webkit-match-parent;

}



cabeçalho,

tbody,

tfoot,

tr,

td,

th {

&#x20; cor da borda: herdar;

&#x20; estilo da borda: sólida;

&#x20; largura-da-borda: 0;

}



rótulo {

&#x20; exibição: inline-block;

}



botão {

&#x20; raio-da-borda: 0;

}



botão:foco:não(:foco-visível) {

&#x20; esboço: 0;

}



entrada,

botão,

selecionar,

optgroup,

área de texto {

&#x20; margem: 0;

&#x20; família-da-fonte: herdar;

&#x20; tamanho-da-fonte: herdar;

&#x20; altura-da-linha: herdar;

}



botão,

selecionar {

&#x20; transformação de texto: nenhuma;

}



\[role=button] {

&#x20; cursor: ponteiro;

}



selecionar {

&#x20; quebra de linha: normal;

}

selecionar:desativado {

&#x20; opacidade: 1;

}



\[lista]:não(\[tipo=data]):não(\[tipo=datahora-local]):não(\[tipo=mês]):não(\[tipo=semana]):não(\[tipo=hora])::-webkit-calendar-picker-indicator {

&#x20; exibir: nenhum !importante;

}



botão,

\[tipo=botão],

\[tipo=redefinir],

\[type=submit] {

&#x20; -webkit-appearance: botão;

}

botão:não(:desativado),

\[type=button]:not(:disabled),

\[type=reset]:not(:disabled),

\[type=submit]:not(:disabled) {

&#x20; cursor: ponteiro;

}



::-moz-focus-inner {

&#x20; preenchimento: 0;

&#x20; estilo de borda: nenhum;

}



área de texto {

&#x20; Redimensionar: vertical;

}



conjunto de campos {

&#x20; largura mínima: 0;

&#x20; preenchimento: 0;

&#x20; margem: 0;

&#x20; borda: 0;

}



lenda {

&#x20; flutuar: esquerda;

&#x20; largura: 100%;

&#x20; preenchimento: 0;

&#x20; margem-inferior: 0,5rem;

&#x20; tamanho-da-fonte: calc(1,275rem + 0,3vw);

&#x20; altura-da-linha: herdar;

}

@media (min-width: 1200px) {

&#x20; lenda {

&#x20;   tamanho da fonte: 1,5rem;

&#x20; }

}

legenda + \* {

&#x20; claro: esquerda;

}



::-webkit-datetime-edit-fields-wrapper,

::-webkit-datetime-edit-text,

::-webkit-datetime-edit-minute,

::-webkit-datetime-edit-hour-field,

::-webkit-datetime-edit-day-field,

::-webkit-datetime-edit-month-field,

::-webkit-datetime-edit-year-field {

&#x20; preenchimento: 0;

}



::-webkit-botão-girar-interno {

&#x20; altura: automática;

}



\[type=search] {

&#x20; deslocamento do contorno: -2px;

&#x20; -webkit-appearance: campo de texto;

}



/\* rtl:raw:

\[tipo="tel"],

\[type="url"],

\[type="email"],

\[tipo="número"] {

&#x20; direção: ltr;

}

\*/

::-webkit-search-decoration {

&#x20; -webkit-appearance: nenhum;

}



::-webkit-color-swatch-wrapper {

&#x20; preenchimento: 0;

}



::-webkit-file-upload-button {

&#x20; fonte: herdar;

&#x20; -webkit-appearance: botão;

}



::botão-seletor-de-arquivos {

&#x20; fonte: herdar;

&#x20; -webkit-appearance: botão;

}



saída {

&#x20; exibição: inline-block;

}



iframe {

&#x20; borda: 0;

}



resumo {

&#x20; exibir: item da lista;

&#x20; cursor: ponteiro;

}



progresso {

&#x20; alinhamento vertical: linha de base;

}



\[escondido] {

&#x20; exibir: nenhum !importante;

}



.liderar {

&#x20; tamanho da fonte: 1,25rem;

&#x20; peso da fonte: 300;

}



.exibir-1 {

&#x20; tamanho-da-fonte: calc(1,625rem + 4,5vw);

&#x20; peso da fonte: 300;

&#x20; altura da linha: 1,2;

}

@media (min-width: 1200px) {

&#x20; .exibir-1 {

&#x20;   tamanho da fonte: 5rem;

&#x20; }

}



.display-2 {

&#x20; tamanho-da-fonte: calc(1,575rem + 3,9vw);

&#x20; peso da fonte: 300;

&#x20; altura da linha: 1,2;

}

@media (min-width: 1200px) {

&#x20; .display-2 {

&#x20;   tamanho da fonte: 4,5rem;

&#x20; }

}



.display-3 {

&#x20; tamanho-da-fonte: calc(1,525rem + 3,3vw);

&#x20; peso da fonte: 300;

&#x20; altura da linha: 1,2;

}

@media (min-width: 1200px) {

&#x20; .display-3 {

&#x20;   tamanho da fonte: 4rem;

&#x20; }

}



.display-4 {

&#x20; tamanho-da-fonte: calc(1,475rem + 2,7vw);

&#x20; peso da fonte: 300;

&#x20; altura da linha: 1,2;

}

@media (min-width: 1200px) {

&#x20; .display-4 {

&#x20;   tamanho da fonte: 3,5rem;

&#x20; }

}



.display-5 {

&#x20; tamanho-da-fonte: calc(1,425rem + 2,1vw);

&#x20; peso da fonte: 300;

&#x20; altura da linha: 1,2;

}

@media (min-width: 1200px) {

&#x20; .display-5 {

&#x20;   tamanho da fonte: 3rem;

&#x20; }

}



.display-6 {

&#x20; tamanho-da-fonte: calc(1,375rem + 1,5vw);

&#x20; peso da fonte: 300;

&#x20; altura da linha: 1,2;

}

@media (min-width: 1200px) {

&#x20; .display-6 {

&#x20;   tamanho da fonte: 2,5rem;

&#x20; }

}



.list-unstyled {

&#x20; preenchimento-esquerdo: 0;

&#x20; estilo de lista: nenhum;

}



.list-inline {

&#x20; preenchimento-esquerdo: 0;

&#x20; estilo de lista: nenhum;

}



.list-inline-item {

&#x20; exibição: inline-block;

}

.list-inline-item:not(:last-child) {

&#x20; margem-direita: 0,5rem;

}



.inicialismo {

&#x20; tamanho da fonte: 0,875em;

&#x20; text-transform: maiúsculas;

}



.blockquote {

&#x20; margem-inferior: 1rem;

&#x20; tamanho da fonte: 1,25rem;

}

.blockquote > :último-filho {

&#x20; margem-inferior: 0;

}



.blockquote-footer {

&#x20; margem-superior: -1rem;

&#x20; margem-inferior: 1rem;

&#x20; tamanho da fonte: 0,875em;

&#x20; cor: #6c757d;

}

.blockquote-footer::before {

&#x20; contente: "- ";

}



.img-fluido {

&#x20; largura máxima: 100%;

&#x20; altura: automática;

}



.img-miniatura {

&#x20; preenchimento: 0,25rem;

&#x20; cor de fundo: var(--bs-body-bg);

&#x20; borda: var(--bs-border-width) var sólido(--bs-border-color);

&#x20; raio da borda: var(--bs-raio da borda);

&#x20; largura máxima: 100%;

&#x20; altura: automática;

}



.figura {

&#x20; exibição: inline-block;

}



.figure-img {

&#x20; margem-inferior: 0,5rem;

&#x20; altura da linha: 1;

}



.figure-caption {

&#x20; tamanho da fonte: 0,875em;

&#x20; cor: var(--bs-cor-secundária);

}



.recipiente,

.contêiner-fluido,

.container-xxl,

.container-xl,

.container-lg,

.container-md,

.container-sm {

&#x20; --bs-gutter-x: 1.5rem;

&#x20; --bs-gutter-y: 0;

&#x20; largura: 100%;

&#x20; padding-right: calc(var(--bs-gutter-x) \* 0.5);

&#x20; padding-left: calc(var(--bs-gutter-x) \* 0.5);

&#x20; margem-direita: automática;

&#x20; margem-esquerda: automática;

}



@media (min-width: 576px) {

&#x20; .container-sm, .container {

&#x20;   largura máxima: 540px;

&#x20; }

}

@media (min-width: 768px) {

&#x20; .container-md, .container-sm, .container {

&#x20;   largura máxima: 720px;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .container-lg, .container-md, .container-sm, .container {

&#x20;   largura máxima: 960px;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .container-xl, .container-lg, .container-md, .container-sm, .container {

&#x20;   largura máxima: 1140px;

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .container-xxl, .container-xl, .container-lg, .container-md, .container-sm, .container {

&#x20;   largura máxima: 1320px;

&#x20; }

}

:raiz {

&#x20; --bs-breakpoint-xs: 0;

&#x20; --bs-breakpoint-sm: 576px;

&#x20; --bs-breakpoint-md: 768px;

&#x20; --bs-breakpoint-lg: 992px;

&#x20; --bs-breakpoint-xl: 1200px;

&#x20; --bs-breakpoint-xxl: 1400px;

}



.linha {

&#x20; --bs-gutter-x: 1.5rem;

&#x20; --bs-gutter-y: 0;

&#x20; Exibir: flexível;

&#x20; flex-wrap: envolver;

&#x20; margem superior: calc(-1 \* var(--bs-gutter-y));

&#x20; margem-direita: calc(-0.5 \* var(--bs-gutter-x));

&#x20; margem-esquerda: calc(-0.5 \* var(--bs-gutter-x));

}

.linha > \* {

&#x20; flex-shrink: 0;

&#x20; largura: 100%;

&#x20; largura máxima: 100%;

&#x20; padding-right: calc(var(--bs-gutter-x) \* 0.5);

&#x20; padding-left: calc(var(--bs-gutter-x) \* 0.5);

&#x20; margem superior: var(--bs-gutter-y);

}



.col {

&#x20; flex: 1 0 0%;

}



.row-cols-auto > \* {

&#x20; flex: 0 0 auto;

&#x20; largura: automática;

}



.row-cols-1 > \* {

&#x20; flex: 0 0 auto;

&#x20; largura: 100%;

}



.row-cols-2 > \* {

&#x20; flex: 0 0 auto;

&#x20; largura: 50%;

}



.row-cols-3 > \* {

&#x20; flex: 0 0 auto;

&#x20; largura: 33,3333333333%;

}



.row-cols-4 > \* {

&#x20; flex: 0 0 auto;

&#x20; largura: 25%;

}



.row-cols-5 > \* {

&#x20; flex: 0 0 auto;

&#x20; largura: 20%;

}



.row-cols-6 > \* {

&#x20; flex: 0 0 auto;

&#x20; largura: 16,6666666667%;

}



.col-auto {

&#x20; flex: 0 0 auto;

&#x20; largura: automática;

}



.col-1 {

&#x20; flex: 0 0 auto;

&#x20; largura: 8,33333333%;

}



.col-2 {

&#x20; flex: 0 0 auto;

&#x20; largura: 16,66666667%;

}



.col-3 {

&#x20; flex: 0 0 auto;

&#x20; largura: 25%;

}



.col-4 {

&#x20; flex: 0 0 auto;

&#x20; largura: 33,33333333%;

}



.col-5 {

&#x20; flex: 0 0 auto;

&#x20; largura: 41,66666667%;

}



.col-6 {

&#x20; flex: 0 0 auto;

&#x20; largura: 50%;

}



.col-7 {

&#x20; flex: 0 0 auto;

&#x20; largura: 58,33333333%;

}



.col-8 {

&#x20; flex: 0 0 auto;

&#x20; largura: 66,66666667%;

}



.col-9 {

&#x20; flex: 0 0 auto;

&#x20; largura: 75%;

}



.col-10 {

&#x20; flex: 0 0 auto;

&#x20; largura: 83,33333333%;

}



.col-11 {

&#x20; flex: 0 0 auto;

&#x20; largura: 91,66666667%;

}



.col-12 {

&#x20; flex: 0 0 auto;

&#x20; largura: 100%;

}



.offset-1 {

&#x20; margem esquerda: 8,33333333%;

}



.offset-2 {

&#x20; margem esquerda: 16,66666667%;

}



.offset-3 {

&#x20; margem esquerda: 25%;

}



.offset-4 {

&#x20; margem esquerda: 33,33333333%;

}



.offset-5 {

&#x20; margem esquerda: 41,66666667%;

}



.offset-6 {

&#x20; margem esquerda: 50%;

}



.offset-7 {

&#x20; margem esquerda: 58,33333333%;

}



.offset-8 {

&#x20; margem esquerda: 66,66666667%;

}



.offset-9 {

&#x20; margem esquerda: 75%;

}



.offset-10 {

&#x20; margem esquerda: 83,33333333%;

}



.offset-11 {

&#x20; margem esquerda: 91,66666667%;

}



.g-0,

.gx-0 {

&#x20; --bs-gutter-x: 0;

}



.g-0,

.gy-0 {

&#x20; --bs-gutter-y: 0;

}



.g-1,

.gx-1 {

&#x20; --bs-gutter-x: 0,25rem;

}



.g-1,

.gy-1 {

&#x20; --bs-gutter-y: 0,25rem;

}



.g-2,

.gx-2 {

&#x20; --bs-gutter-x: 0.5rem;

}



.g-2,

.gy-2 {

&#x20; --bs-gutter-y: 0,5rem;

}



.g-3,

.gx-3 {

&#x20; --bs-gutter-x: 1rem;

}



.g-3,

.gy-3 {

&#x20; --bs-gutter-y: 1rem;

}



.g-4,

.gx-4 {

&#x20; --bs-gutter-x: 1.5rem;

}



.g-4,

.gy-4 {

&#x20; --bs-gutter-y: 1,5rem;

}



.g-5,

.gx-5 {

&#x20; --bs-gutter-x: 3rem;

}



.g-5,

.gy-5 {

&#x20; --bs-gutter-y: 3rem;

}



@media (min-width: 576px) {

&#x20; .col-sm {

&#x20;   flex: 1 0 0%;

&#x20; }

&#x20; .row-cols-sm-auto > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .row-cols-sm-1 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .row-cols-sm-2 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .row-cols-sm-3 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,3333333333%;

&#x20; }

&#x20; .row-cols-sm-4 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .row-cols-sm-5 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 20%;

&#x20; }

&#x20; .row-cols-sm-6 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,6666666667%;

&#x20; }

&#x20; .col-sm-auto {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .col-sm-1 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 8,33333333%;

&#x20; }

&#x20; .col-sm-2 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,66666667%;

&#x20; }

&#x20; .col-sm-3 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .col-sm-4 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,33333333%;

&#x20; }

&#x20; .col-sm-5 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 41,66666667%;

&#x20; }

&#x20; .col-sm-6 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .col-sm-7 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 58,33333333%;

&#x20; }

&#x20; .col-sm-8 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 66,66666667%;

&#x20; }

&#x20; .col-sm-9 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 75%;

&#x20; }

&#x20; .col-sm-10 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 83,33333333%;

&#x20; }

&#x20; .col-sm-11 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 91,66666667%;

&#x20; }

&#x20; .col-sm-12 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .offset-sm-0 {

&#x20;   margem-esquerda: 0;

&#x20; }

&#x20; .offset-sm-1 {

&#x20;   margem esquerda: 8,33333333%;

&#x20; }

&#x20; .offset-sm-2 {

&#x20;   margem esquerda: 16,66666667%;

&#x20; }

&#x20; .offset-sm-3 {

&#x20;   margem esquerda: 25%;

&#x20; }

&#x20; .offset-sm-4 {

&#x20;   margem esquerda: 33,33333333%;

&#x20; }

&#x20; .offset-sm-5 {

&#x20;   margem esquerda: 41,66666667%;

&#x20; }

&#x20; .offset-sm-6 {

&#x20;   margem esquerda: 50%;

&#x20; }

&#x20; .offset-sm-7 {

&#x20;   margem esquerda: 58,33333333%;

&#x20; }

&#x20; .offset-sm-8 {

&#x20;   margem esquerda: 66,66666667%;

&#x20; }

&#x20; .offset-sm-9 {

&#x20;   margem esquerda: 75%;

&#x20; }

&#x20; .offset-sm-10 {

&#x20;   margem esquerda: 83,33333333%;

&#x20; }

&#x20; .offset-sm-11 {

&#x20;   margem esquerda: 91,66666667%;

&#x20; }

&#x20; .g-sm-0,

&#x20; .gx-sm-0 {

&#x20;   --bs-gutter-x: 0;

&#x20; }

&#x20; .g-sm-0,

&#x20; .gy-sm-0 {

&#x20;   --bs-gutter-y: 0;

&#x20; }

&#x20; .g-sm-1,

&#x20; .gx-sm-1 {

&#x20;   --bs-gutter-x: 0,25rem;

&#x20; }

&#x20; .g-sm-1,

&#x20; .gy-sm-1 {

&#x20;   --bs-gutter-y: 0,25rem;

&#x20; }

&#x20; .g-sm-2,

&#x20; .gx-sm-2 {

&#x20;   --bs-gutter-x: 0.5rem;

&#x20; }

&#x20; .g-sm-2,

&#x20; .gy-sm-2 {

&#x20;   --bs-gutter-y: 0,5rem;

&#x20; }

&#x20; .g-sm-3,

&#x20; .gx-sm-3 {

&#x20;   --bs-gutter-x: 1rem;

&#x20; }

&#x20; .g-sm-3,

&#x20; .gy-sm-3 {

&#x20;   --bs-gutter-y: 1rem;

&#x20; }

&#x20; .g-sm-4,

&#x20; .gx-sm-4 {

&#x20;   --bs-gutter-x: 1.5rem;

&#x20; }

&#x20; .g-sm-4,

&#x20; .gy-sm-4 {

&#x20;   --bs-gutter-y: 1,5rem;

&#x20; }

&#x20; .g-sm-5,

&#x20; .gx-sm-5 {

&#x20;   --bs-gutter-x: 3rem;

&#x20; }

&#x20; .g-sm-5,

&#x20; .gy-sm-5 {

&#x20;   --bs-gutter-y: 3rem;

&#x20; }

}

@media (min-width: 768px) {

&#x20; .col-md {

&#x20;   flex: 1 0 0%;

&#x20; }

&#x20; .row-cols-md-auto > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .row-cols-md-1 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .row-cols-md-2 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .row-cols-md-3 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,3333333333%;

&#x20; }

&#x20; .row-cols-md-4 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .row-cols-md-5 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 20%;

&#x20; }

&#x20; .row-cols-md-6 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,6666666667%;

&#x20; }

&#x20; .col-md-auto {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .col-md-1 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 8,33333333%;

&#x20; }

&#x20; .col-md-2 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,66666667%;

&#x20; }

&#x20; .col-md-3 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .col-md-4 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,33333333%;

&#x20; }

&#x20; .col-md-5 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 41,66666667%;

&#x20; }

&#x20; .col-md-6 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .col-md-7 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 58,33333333%;

&#x20; }

&#x20; .col-md-8 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 66,66666667%;

&#x20; }

&#x20; .col-md-9 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 75%;

&#x20; }

&#x20; .col-md-10 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 83,33333333%;

&#x20; }

&#x20; .col-md-11 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 91,66666667%;

&#x20; }

&#x20; .col-md-12 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .offset-md-0 {

&#x20;   margem-esquerda: 0;

&#x20; }

&#x20; .offset-md-1 {

&#x20;   margem esquerda: 8,33333333%;

&#x20; }

&#x20; .offset-md-2 {

&#x20;   margem esquerda: 16,66666667%;

&#x20; }

&#x20; .offset-md-3 {

&#x20;   margem esquerda: 25%;

&#x20; }

&#x20; .offset-md-4 {

&#x20;   margem esquerda: 33,33333333%;

&#x20; }

&#x20; .offset-md-5 {

&#x20;   margem esquerda: 41,66666667%;

&#x20; }

&#x20; .offset-md-6 {

&#x20;   margem esquerda: 50%;

&#x20; }

&#x20; .offset-md-7 {

&#x20;   margem esquerda: 58,33333333%;

&#x20; }

&#x20; .offset-md-8 {

&#x20;   margem esquerda: 66,66666667%;

&#x20; }

&#x20; .offset-md-9 {

&#x20;   margem esquerda: 75%;

&#x20; }

&#x20; .offset-md-10 {

&#x20;   margem esquerda: 83,33333333%;

&#x20; }

&#x20; .offset-md-11 {

&#x20;   margem esquerda: 91,66666667%;

&#x20; }

&#x20; .g-md-0,

&#x20; .gx-md-0 {

&#x20;   --bs-gutter-x: 0;

&#x20; }

&#x20; .g-md-0,

&#x20; .gy-md-0 {

&#x20;   --bs-gutter-y: 0;

&#x20; }

&#x20; .g-md-1,

&#x20; .gx-md-1 {

&#x20;   --bs-gutter-x: 0,25rem;

&#x20; }

&#x20; .g-md-1,

&#x20; .gy-md-1 {

&#x20;   --bs-gutter-y: 0,25rem;

&#x20; }

&#x20; .g-md-2,

&#x20; .gx-md-2 {

&#x20;   --bs-gutter-x: 0.5rem;

&#x20; }

&#x20; .g-md-2,

&#x20; .gy-md-2 {

&#x20;   --bs-gutter-y: 0,5rem;

&#x20; }

&#x20; .g-md-3,

&#x20; .gx-md-3 {

&#x20;   --bs-gutter-x: 1rem;

&#x20; }

&#x20; .g-md-3,

&#x20; .gy-md-3 {

&#x20;   --bs-gutter-y: 1rem;

&#x20; }

&#x20; .g-md-4,

&#x20; .gx-md-4 {

&#x20;   --bs-gutter-x: 1.5rem;

&#x20; }

&#x20; .g-md-4,

&#x20; .gy-md-4 {

&#x20;   --bs-gutter-y: 1,5rem;

&#x20; }

&#x20; .g-md-5,

&#x20; .gx-md-5 {

&#x20;   --bs-gutter-x: 3rem;

&#x20; }

&#x20; .g-md-5,

&#x20; .gy-md-5 {

&#x20;   --bs-gutter-y: 3rem;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .col-lg {

&#x20;   flex: 1 0 0%;

&#x20; }

&#x20; .row-cols-lg-auto > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .row-cols-lg-1 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .row-cols-lg-2 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .row-cols-lg-3 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,3333333333%;

&#x20; }

&#x20; .row-cols-lg-4 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .row-cols-lg-5 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 20%;

&#x20; }

&#x20; .row-cols-lg-6 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,6666666667%;

&#x20; }

&#x20; .col-lg-auto {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .col-lg-1 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 8,33333333%;

&#x20; }

&#x20; .col-lg-2 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,66666667%;

&#x20; }

&#x20; .col-lg-3 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .col-lg-4 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,33333333%;

&#x20; }

&#x20; .col-lg-5 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 41,66666667%;

&#x20; }

&#x20; .col-lg-6 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .col-lg-7 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 58,33333333%;

&#x20; }

&#x20; .col-lg-8 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 66,66666667%;

&#x20; }

&#x20; .col-lg-9 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 75%;

&#x20; }

&#x20; .col-lg-10 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 83,33333333%;

&#x20; }

&#x20; .col-lg-11 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 91,66666667%;

&#x20; }

&#x20; .col-lg-12 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .offset-lg-0 {

&#x20;   margem-esquerda: 0;

&#x20; }

&#x20; .offset-lg-1 {

&#x20;   margem esquerda: 8,33333333%;

&#x20; }

&#x20; .offset-lg-2 {

&#x20;   margem esquerda: 16,66666667%;

&#x20; }

&#x20; .offset-lg-3 {

&#x20;   margem esquerda: 25%;

&#x20; }

&#x20; .offset-lg-4 {

&#x20;   margem esquerda: 33,33333333%;

&#x20; }

&#x20; .offset-lg-5 {

&#x20;   margem esquerda: 41,66666667%;

&#x20; }

&#x20; .offset-lg-6 {

&#x20;   margem esquerda: 50%;

&#x20; }

&#x20; .offset-lg-7 {

&#x20;   margem esquerda: 58,33333333%;

&#x20; }

&#x20; .offset-lg-8 {

&#x20;   margem esquerda: 66,66666667%;

&#x20; }

&#x20; .offset-lg-9 {

&#x20;   margem esquerda: 75%;

&#x20; }

&#x20; .offset-lg-10 {

&#x20;   margem esquerda: 83,33333333%;

&#x20; }

&#x20; .offset-lg-11 {

&#x20;   margem esquerda: 91,66666667%;

&#x20; }

&#x20; .g-lg-0,

&#x20; .gx-lg-0 {

&#x20;   --bs-gutter-x: 0;

&#x20; }

&#x20; .g-lg-0,

&#x20; .gy-lg-0 {

&#x20;   --bs-gutter-y: 0;

&#x20; }

&#x20; .g-lg-1,

&#x20; .gx-lg-1 {

&#x20;   --bs-gutter-x: 0,25rem;

&#x20; }

&#x20; .g-lg-1,

&#x20; .gy-lg-1 {

&#x20;   --bs-gutter-y: 0,25rem;

&#x20; }

&#x20; .g-lg-2,

&#x20; .gx-lg-2 {

&#x20;   --bs-gutter-x: 0.5rem;

&#x20; }

&#x20; .g-lg-2,

&#x20; .gy-lg-2 {

&#x20;   --bs-gutter-y: 0,5rem;

&#x20; }

&#x20; .g-lg-3,

&#x20; .gx-lg-3 {

&#x20;   --bs-gutter-x: 1rem;

&#x20; }

&#x20; .g-lg-3,

&#x20; .gy-lg-3 {

&#x20;   --bs-gutter-y: 1rem;

&#x20; }

&#x20; .g-lg-4,

&#x20; .gx-lg-4 {

&#x20;   --bs-gutter-x: 1.5rem;

&#x20; }

&#x20; .g-lg-4,

&#x20; .gy-lg-4 {

&#x20;   --bs-gutter-y: 1,5rem;

&#x20; }

&#x20; .g-lg-5,

&#x20; .gx-lg-5 {

&#x20;   --bs-gutter-x: 3rem;

&#x20; }

&#x20; .g-lg-5,

&#x20; .gy-lg-5 {

&#x20;   --bs-gutter-y: 3rem;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .col-xl {

&#x20;   flex: 1 0 0%;

&#x20; }

&#x20; .row-cols-xl-auto > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .row-cols-xl-1 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .row-cols-xl-2 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .row-cols-xl-3 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,3333333333%;

&#x20; }

&#x20; .row-cols-xl-4 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .row-cols-xl-5 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 20%;

&#x20; }

&#x20; .row-cols-xl-6 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,6666666667%;

&#x20; }

&#x20; .col-xl-auto {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .col-xl-1 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 8,33333333%;

&#x20; }

&#x20; .col-xl-2 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,66666667%;

&#x20; }

&#x20; .col-xl-3 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .col-xl-4 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,33333333%;

&#x20; }

&#x20; .col-xl-5 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 41,66666667%;

&#x20; }

&#x20; .col-xl-6 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .col-xl-7 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 58,33333333%;

&#x20; }

&#x20; .col-xl-8 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 66,66666667%;

&#x20; }

&#x20; .col-xl-9 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 75%;

&#x20; }

&#x20; .col-xl-10 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 83,33333333%;

&#x20; }

&#x20; .col-xl-11 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 91,66666667%;

&#x20; }

&#x20; .col-xl-12 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .offset-xl-0 {

&#x20;   margem-esquerda: 0;

&#x20; }

&#x20; .offset-xl-1 {

&#x20;   margem esquerda: 8,33333333%;

&#x20; }

&#x20; .offset-xl-2 {

&#x20;   margem esquerda: 16,66666667%;

&#x20; }

&#x20; .offset-xl-3 {

&#x20;   margem esquerda: 25%;

&#x20; }

&#x20; .offset-xl-4 {

&#x20;   margem esquerda: 33,33333333%;

&#x20; }

&#x20; .offset-xl-5 {

&#x20;   margem esquerda: 41,66666667%;

&#x20; }

&#x20; .offset-xl-6 {

&#x20;   margem esquerda: 50%;

&#x20; }

&#x20; .offset-xl-7 {

&#x20;   margem esquerda: 58,33333333%;

&#x20; }

&#x20; .offset-xl-8 {

&#x20;   margem esquerda: 66,66666667%;

&#x20; }

&#x20; .offset-xl-9 {

&#x20;   margem esquerda: 75%;

&#x20; }

&#x20; .offset-xl-10 {

&#x20;   margem esquerda: 83,33333333%;

&#x20; }

&#x20; .offset-xl-11 {

&#x20;   margem esquerda: 91,66666667%;

&#x20; }

&#x20; .g-xl-0,

&#x20; .gx-xl-0 {

&#x20;   --bs-gutter-x: 0;

&#x20; }

&#x20; .g-xl-0,

&#x20; .gy-xl-0 {

&#x20;   --bs-gutter-y: 0;

&#x20; }

&#x20; .g-xl-1,

&#x20; .gx-xl-1 {

&#x20;   --bs-gutter-x: 0,25rem;

&#x20; }

&#x20; .g-xl-1,

&#x20; .gy-xl-1 {

&#x20;   --bs-gutter-y: 0,25rem;

&#x20; }

&#x20; .g-xl-2,

&#x20; .gx-xl-2 {

&#x20;   --bs-gutter-x: 0.5rem;

&#x20; }

&#x20; .g-xl-2,

&#x20; .gy-xl-2 {

&#x20;   --bs-gutter-y: 0,5rem;

&#x20; }

&#x20; .g-xl-3,

&#x20; .gx-xl-3 {

&#x20;   --bs-gutter-x: 1rem;

&#x20; }

&#x20; .g-xl-3,

&#x20; .gy-xl-3 {

&#x20;   --bs-gutter-y: 1rem;

&#x20; }

&#x20; .g-xl-4,

&#x20; .gx-xl-4 {

&#x20;   --bs-gutter-x: 1.5rem;

&#x20; }

&#x20; .g-xl-4,

&#x20; .gy-xl-4 {

&#x20;   --bs-gutter-y: 1,5rem;

&#x20; }

&#x20; .g-xl-5,

&#x20; .gx-xl-5 {

&#x20;   --bs-gutter-x: 3rem;

&#x20; }

&#x20; .g-xl-5,

&#x20; .gy-xl-5 {

&#x20;   --bs-gutter-y: 3rem;

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .col-xxl {

&#x20;   flex: 1 0 0%;

&#x20; }

&#x20; .row-cols-xxl-auto > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .row-cols-xxl-1 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .row-cols-xxl-2 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .row-cols-xxl-3 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,3333333333%;

&#x20; }

&#x20; .row-cols-xxl-4 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .row-cols-xxl-5 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 20%;

&#x20; }

&#x20; .row-cols-xxl-6 > \* {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,6666666667%;

&#x20; }

&#x20; .col-xxl-auto {

&#x20;   flex: 0 0 auto;

&#x20;   largura: automática;

&#x20; }

&#x20; .col-xxl-1 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 8,33333333%;

&#x20; }

&#x20; .col-xxl-2 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 16,66666667%;

&#x20; }

&#x20; .col-xxl-3 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 25%;

&#x20; }

&#x20; .col-xxl-4 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 33,33333333%;

&#x20; }

&#x20; .col-xxl-5 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 41,66666667%;

&#x20; }

&#x20; .col-xxl-6 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 50%;

&#x20; }

&#x20; .col-xxl-7 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 58,33333333%;

&#x20; }

&#x20; .col-xxl-8 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 66,66666667%;

&#x20; }

&#x20; .col-xxl-9 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 75%;

&#x20; }

&#x20; .col-xxl-10 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 83,33333333%;

&#x20; }

&#x20; .col-xxl-11 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 91,66666667%;

&#x20; }

&#x20; .col-xxl-12 {

&#x20;   flex: 0 0 auto;

&#x20;   largura: 100%;

&#x20; }

&#x20; .offset-xxl-0 {

&#x20;   margem-esquerda: 0;

&#x20; }

&#x20; .offset-xxl-1 {

&#x20;   margem esquerda: 8,33333333%;

&#x20; }

&#x20; .offset-xxl-2 {

&#x20;   margem esquerda: 16,66666667%;

&#x20; }

&#x20; .offset-xxl-3 {

&#x20;   margem esquerda: 25%;

&#x20; }

&#x20; .offset-xxl-4 {

&#x20;   margem esquerda: 33,33333333%;

&#x20; }

&#x20; .offset-xxl-5 {

&#x20;   margem esquerda: 41,66666667%;

&#x20; }

&#x20; .offset-xxl-6 {

&#x20;   margem esquerda: 50%;

&#x20; }

&#x20; .offset-xxl-7 {

&#x20;   margem esquerda: 58,33333333%;

&#x20; }

&#x20; .offset-xxl-8 {

&#x20;   margem esquerda: 66,66666667%;

&#x20; }

&#x20; .offset-xxl-9 {

&#x20;   margem esquerda: 75%;

&#x20; }

&#x20; .offset-xxl-10 {

&#x20;   margem esquerda: 83,33333333%;

&#x20; }

&#x20; .offset-xxl-11 {

&#x20;   margem esquerda: 91,66666667%;

&#x20; }

&#x20; .g-xxl-0,

&#x20; .gx-xxl-0 {

&#x20;   --bs-gutter-x: 0;

&#x20; }

&#x20; .g-xxl-0,

&#x20; .gy-xxl-0 {

&#x20;   --bs-gutter-y: 0;

&#x20; }

&#x20; .g-xxl-1,

&#x20; .gx-xxl-1 {

&#x20;   --bs-gutter-x: 0,25rem;

&#x20; }

&#x20; .g-xxl-1,

&#x20; .gy-xxl-1 {

&#x20;   --bs-gutter-y: 0,25rem;

&#x20; }

&#x20; .g-xxl-2,

&#x20; .gx-xxl-2 {

&#x20;   --bs-gutter-x: 0.5rem;

&#x20; }

&#x20; .g-xxl-2,

&#x20; .gy-xxl-2 {

&#x20;   --bs-gutter-y: 0,5rem;

&#x20; }

&#x20; .g-xxl-3,

&#x20; .gx-xxl-3 {

&#x20;   --bs-gutter-x: 1rem;

&#x20; }

&#x20; .g-xxl-3,

&#x20; .gy-xxl-3 {

&#x20;   --bs-gutter-y: 1rem;

&#x20; }

&#x20; .g-xxl-4,

&#x20; .gx-xxl-4 {

&#x20;   --bs-gutter-x: 1.5rem;

&#x20; }

&#x20; .g-xxl-4,

&#x20; .gy-xxl-4 {

&#x20;   --bs-gutter-y: 1,5rem;

&#x20; }

&#x20; .g-xxl-5,

&#x20; .gx-xxl-5 {

&#x20;   --bs-gutter-x: 3rem;

&#x20; }

&#x20; .g-xxl-5,

&#x20; .gy-xxl-5 {

&#x20;   --bs-gutter-y: 3rem;

&#x20; }

}

.mesa {

&#x20; --bs-table-color-type: inicial;

&#x20; --bs-table-bg-type: inicial;

&#x20; --bs-table-color-state: inicial;

&#x20; --bs-table-bg-state: inicial;

&#x20; --bs-table-color: var(--bs-body-color);

&#x20; --bs-tabela-bg: var(--bs-body-bg);

&#x20; --bs-table-border-color: var(--bs-border-color);

&#x20; --bs-table-accent-bg: transparente;

&#x20; --bs-table-striped-color: var(--bs-body-color);

&#x20; --bs-table-striped-bg: rgba(0, 0, 0, 0.05);

&#x20; --bs-table-active-color: var(--bs-body-color);

&#x20; --bs-table-active-bg: rgba(0, 0, 0, 0.1);

&#x20; --bs-table-hover-color: var(--bs-body-color);

&#x20; --bs-table-hover-bg: rgba(0, 0, 0, 0.075);

&#x20; largura: 100%;

&#x20; margem-inferior: 1rem;

&#x20; alinhamento vertical: superior;

&#x20; cor-da-borda: var(--bs-table-border-color);

}

.table > :not(caption) > \* > \* {

&#x20; preenchimento: 0,5rem 0,5rem;

&#x20; cor: var(--bs-table-color-state, var(--bs-table-color-type, var(--bs-table-color)));

&#x20; cor de fundo: var(--bs-table-bg);

&#x20; largura-inferior-da-borda: var(--bs-largura-da-borda);

&#x20; box-shadow: inset 0 0 0 9999px var(--bs-table-bg-state, var(--bs-table-bg-type, var(--bs-table-accent-bg)));

}

.table > tbody {

&#x20; alinhamento vertical: herdar;

}

.table > cabeçalho {

&#x20; alinhamento vertical: inferior;

}



.divisor-de-grupo-de-tabelas {

&#x20; borda-superior: calc(var(--bs-border-width) \* 2) sólida cor-atual;

}



.caption-top {

&#x20; legenda-lateral: superior;

}



.table-sm > :not(caption) > \* > \* {

&#x20; preenchimento: 0,25rem 0,25rem;

}



.table-bordered > :not(caption) > \* {

&#x20; largura-da-borda: var(--bs-border-width) 0;

}

.table-bordered > :not(caption) > \* > \* {

&#x20; largura-da-borda: 0 var(--bs-border-width);

}



.table-borderless > :not(caption) > \* > \* {

&#x20; largura-inferior-da-borda: 0;

}

.table-borderless > :not(:first-child) {

&#x20; largura-superior-da-borda: 0;

}



.table-striped > tbody > tr:nth-of-type(odd) > \* {

&#x20; --bs-table-color-type: var(--bs-table-striped-color);

&#x20; --bs-table-bg-type: var(--bs-table-striped-bg);

}



.table-striped-columns > :not(caption) > tr > :nth-child(even) {

&#x20; --bs-table-color-type: var(--bs-table-striped-color);

&#x20; --bs-table-bg-type: var(--bs-table-striped-bg);

}



.table-active {

&#x20; --bs-table-color-state: var(--bs-table-active-color);

&#x20; --bs-table-bg-state: var(--bs-table-active-bg);

}



.table-hover > tbody > tr:hover > \* {

&#x20; --bs-table-color-state: var(--bs-table-hover-color);

&#x20; --bs-table-bg-state: var(--bs-table-hover-bg);

}



.table-primary {

&#x20; --bs-table-color: #000;

&#x20; --bs-table-bg: #cfe2ff;

&#x20; --bs-table-border-color: #bacbe6;

&#x20; --bs-table-striped-bg: #c5d7f2;

&#x20; --bs-table-striped-color: #000;

&#x20; --bs-table-active-bg: #bacbe6;

&#x20; --bs-table-active-color: #000;

&#x20; --bs-table-hover-bg: #bfd1ec;

&#x20; --bs-table-hover-color: #000;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-secondary {

&#x20; --bs-table-color: #000;

&#x20; --bs-table-bg: #e2e3e5;

&#x20; --bs-table-border-color: #cbccce;

&#x20; --bs-table-striped-bg: #d7d8da;

&#x20; --bs-table-striped-color: #000;

&#x20; --bs-table-active-bg: #cbccce;

&#x20; --bs-table-active-color: #000;

&#x20; --bs-table-hover-bg: #d1d2d4;

&#x20; --bs-table-hover-color: #000;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-success {

&#x20; --bs-table-color: #000;

&#x20; --bs-table-bg: #d1e7dd;

&#x20; --bs-table-border-color: #bcd0c7;

&#x20; --bs-table-striped-bg: #c7dbd2;

&#x20; --bs-table-striped-color: #000;

&#x20; --bs-table-active-bg: #bcd0c7;

&#x20; --bs-table-active-color: #000;

&#x20; --bs-table-hover-bg: #c1d6cc;

&#x20; --bs-table-hover-color: #000;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-info {

&#x20; --bs-table-color: #000;

&#x20; --bs-table-bg: #cff4fc;

&#x20; --bs-table-border-color: #badce3;

&#x20; --bs-table-striped-bg: #c5e8ef;

&#x20; --bs-table-striped-color: #000;

&#x20; --bs-table-active-bg: #badce3;

&#x20; --bs-table-active-color: #000;

&#x20; --bs-table-hover-bg: #bfe2e9;

&#x20; --bs-table-hover-color: #000;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-warning {

&#x20; --bs-table-color: #000;

&#x20; --bs-table-bg: #fff3cd;

&#x20; --bs-table-border-color: #e6dbb9;

&#x20; --bs-table-striped-bg: #f2e7c3;

&#x20; --bs-table-striped-color: #000;

&#x20; --bs-table-active-bg: #e6dbb9;

&#x20; --bs-table-active-color: #000;

&#x20; --bs-table-hover-bg: #ece1be;

&#x20; --bs-table-hover-color: #000;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-danger {

&#x20; --bs-table-color: #000;

&#x20; --bs-table-bg: #f8d7da;

&#x20; --bs-table-border-color: #dfc2c4;

&#x20; --bs-table-striped-bg: #eccccf;

&#x20; --bs-table-striped-color: #000;

&#x20; --bs-table-active-bg: #dfc2c4;

&#x20; --bs-table-active-color: #000;

&#x20; --bs-table-hover-bg: #e5c7ca;

&#x20; --bs-table-hover-color: #000;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-light {

&#x20; --bs-table-color: #000;

&#x20; --bs-table-bg: #f8f9fa;

&#x20; --bs-table-border-color: #dfe0e1;

&#x20; --bs-table-striped-bg: #ecedee;

&#x20; --bs-table-striped-color: #000;

&#x20; --bs-table-active-bg: #dfe0e1;

&#x20; --bs-table-active-color: #000;

&#x20; --bs-table-hover-bg: #e5e6e7;

&#x20; --bs-table-hover-color: #000;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-dark {

&#x20; --bs-table-color: #fff;

&#x20; --bs-table-bg: #212529;

&#x20; --bs-table-border-color: #373b3e;

&#x20; --bs-table-striped-bg: #2c3034;

&#x20; --bs-table-striped-color: #fff;

&#x20; --bs-table-active-bg: #373b3e;

&#x20; --bs-table-active-color: #fff;

&#x20; --bs-table-hover-bg: #323539;

&#x20; --bs-table-hover-color: #fff;

&#x20; cor: var(--bs-table-color);

&#x20; cor-da-borda: var(--bs-table-border-color);

}



.table-responsive {

&#x20; overflow-x: automático;

&#x20; -webkit-overflow-scrolling: toque;

}



@media (max-width: 575.98px) {

&#x20; .table-responsive-sm {

&#x20;   overflow-x: automático;

&#x20;   -webkit-overflow-scrolling: toque;

&#x20; }

}

@media (max-width: 767.98px) {

&#x20; .table-responsive-md {

&#x20;   overflow-x: automático;

&#x20;   -webkit-overflow-scrolling: toque;

&#x20; }

}

@media (max-width: 991.98px) {

&#x20; .table-responsive-lg {

&#x20;   overflow-x: automático;

&#x20;   -webkit-overflow-scrolling: toque;

&#x20; }

}

@media (max-width: 1199.98px) {

&#x20; .table-responsive-xl {

&#x20;   overflow-x: automático;

&#x20;   -webkit-overflow-scrolling: toque;

&#x20; }

}

@media (max-width: 1399.98px) {

&#x20; .table-responsive-xxl {

&#x20;   overflow-x: automático;

&#x20;   -webkit-overflow-scrolling: toque;

&#x20; }

}

.form-label {

&#x20; margem-inferior: 0,5rem;

}



.col-form-label {

&#x20; padding-top: calc(0.375rem + var(--bs-border-width));

&#x20; padding-bottom: calc(0.375rem + var(--bs-border-width));

&#x20; margem-inferior: 0;

&#x20; tamanho-da-fonte: herdar;

&#x20; altura da linha: 1,5;

}



.col-form-label-lg {

&#x20; padding-top: calc(0.5rem + var(--bs-border-width));

&#x20; padding-bottom: calc(0.5rem + var(--bs-border-width));

&#x20; tamanho da fonte: 1,25rem;

}



.col-form-label-sm {

&#x20; padding-top: calc(0.25rem + var(--bs-border-width));

&#x20; padding-bottom: calc(0.25rem + var(--bs-border-width));

&#x20; tamanho da fonte: 0,875rem;

}



.form-texto {

&#x20; margem superior: 0,25rem;

&#x20; tamanho da fonte: 0,875em;

&#x20; cor: var(--bs-cor-secundária);

}



.form-control {

&#x20; exibir: bloco;

&#x20; largura: 100%;

&#x20; preenchimento: 0,375rem 0,75rem;

&#x20; tamanho da fonte: 1rem;

&#x20; peso da fonte: 400;

&#x20; altura da linha: 1,5;

&#x20; cor: var(--bs-body-color);

&#x20; cor de fundo: var(--bs-body-bg);

&#x20; background-clip: padding-box;

&#x20; borda: var(--bs-border-width) var sólido(--bs-border-color);

&#x20; -webkit-appearance: nenhum;

&#x20; -moz-appearance: nenhuma;

&#x20; Aparência: nenhuma;

&#x20; raio da borda: var(--bs-raio da borda);

&#x20; transição: cor da borda 0,15s com suavização de entrada e saída, sombra da caixa 0,15s com suavização de entrada e saída;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .form-control {

&#x20;   transição: nenhuma;

&#x20; }

}

.form-control\[type=file] {

&#x20; overflow: oculto;

}

.form-control\[type=file]:not(:disabled):not(\[readonly]) {

&#x20; cursor: ponteiro;

}

.form-control:focus {

&#x20; cor: var(--bs-body-color);

&#x20; cor de fundo: var(--bs-body-bg);

&#x20; cor da borda: #86b7fe;

&#x20; esboço: 0;

&#x20; box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

}

.form-control::-webkit-date-and-time-value {

&#x20; largura mínima: 85px;

&#x20; altura: 1,5em;

&#x20; margem: 0;

}

.form-control::-webkit-datetime-edit {

&#x20; exibir: bloco;

&#x20; preenchimento: 0;

}

.form-control::-moz-placeholder {

&#x20; cor: var(--bs-cor-secundária);

&#x20; opacidade: 1;

}

.form-control::placeholder {

&#x20; cor: var(--bs-cor-secundária);

&#x20; opacidade: 1;

}

.form-control:disabled {

&#x20; cor de fundo: var(--bs-secondary-bg);

&#x20; opacidade: 1;

}

.form-control::-webkit-file-upload-button {

&#x20; preenchimento: 0,375rem 0,75rem;

&#x20; margem: -0,375rem -0,75rem;

&#x20; -webkit-margin-end: 0.75rem;

&#x20; margem-em-linha-final: 0,75rem;

&#x20; cor: var(--bs-body-color);

&#x20; cor de fundo: var(--bs-tertiary-bg);

&#x20; eventos-ponteiro: nenhum;

&#x20; cor da borda: herdar;

&#x20; estilo da borda: sólida;

&#x20; largura-da-borda: 0;

&#x20; largura-final-da-borda-em-linha: var(--bs-border-width);

&#x20; raio-da-borda: 0;

&#x20; -webkit-transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;

&#x20; transição: cor 0,15s ease-in-out, cor de fundo 0,15s ease-in-out, cor da borda 0,15s ease-in-out, sombra da caixa 0,15s ease-in-out;

}

.form-control::file-selector-button {

&#x20; preenchimento: 0,375rem 0,75rem;

&#x20; margem: -0,375rem -0,75rem;

&#x20; -webkit-margin-end: 0.75rem;

&#x20; margem-em-linha-final: 0,75rem;

&#x20; cor: var(--bs-body-color);

&#x20; cor de fundo: var(--bs-tertiary-bg);

&#x20; eventos-ponteiro: nenhum;

&#x20; cor da borda: herdar;

&#x20; estilo da borda: sólida;

&#x20; largura-da-borda: 0;

&#x20; largura-final-da-borda-em-linha: var(--bs-border-width);

&#x20; raio-da-borda: 0;

&#x20; transição: cor 0,15s ease-in-out, cor de fundo 0,15s ease-in-out, cor da borda 0,15s ease-in-out, sombra da caixa 0,15s ease-in-out;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .form-control::-webkit-file-upload-button {

&#x20;   -webkit-transition: nenhum;

&#x20;   transição: nenhuma;

&#x20; }

&#x20; .form-control::file-selector-button {

&#x20;   transição: nenhuma;

&#x20; }

}

.form-control:hover:not(:disabled):not(\[readonly])::-webkit-file-upload-button {

&#x20; cor de fundo: var(--bs-secondary-bg);

}

.form-control:hover:not(:disabled):not(\[readonly])::file-selector-button {

&#x20; cor de fundo: var(--bs-secondary-bg);

}



.form-control-plaintext {

&#x20; exibir: bloco;

&#x20; largura: 100%;

&#x20; preenchimento: 0,375rem 0;

&#x20; margem-inferior: 0;

&#x20; altura da linha: 1,5;

&#x20; cor: var(--bs-body-color);

&#x20; cor de fundo: transparente;

&#x20; Borda: sólida e transparente;

&#x20; largura-da-borda: var(--bs-border-width) 0;

}

.form-control-plaintext:focus {

&#x20; esboço: 0;

}

.form-control-plaintext.form-control-sm, .form-control-plaintext.form-control-lg {

&#x20; preenchimento à direita: 0;

&#x20; preenchimento-esquerdo: 0;

}



.form-control-sm {

&#x20; altura-mínima: calc(1.5em + 0.5rem + calc(var(--bs-border-width) \* 2));

&#x20; preenchimento: 0,25rem 0,5rem;

&#x20; tamanho da fonte: 0,875rem;

&#x20; raio da borda: var(--bs-border-radius-sm);

}

.form-control-sm::-webkit-file-upload-button {

&#x20; preenchimento: 0,25rem 0,5rem;

&#x20; margem: -0,25rem -0,5rem;

&#x20; -webkit-margin-end: 0.5rem;

&#x20; margem-em-linha-final: 0,5rem;

}

.form-control-sm::file-selector-button {

&#x20; preenchimento: 0,25rem 0,5rem;

&#x20; margem: -0,25rem -0,5rem;

&#x20; -webkit-margin-end: 0.5rem;

&#x20; margem-em-linha-final: 0,5rem;

}



.form-control-lg {

&#x20; altura-mínima: calc(1.5em + 1rem + calc(var(--bs-border-width) \* 2));

&#x20; preenchimento: 0,5rem 1rem;

&#x20; tamanho da fonte: 1,25rem;

&#x20; raio da borda: var(-bs-border-radius-lg);

}

.form-control-lg::-webkit-file-upload-button {

&#x20; preenchimento: 0,5rem 1rem;

&#x20; margem: -0,5rem -1rem;

&#x20; -webkit-margin-end: 1rem;

&#x20; margem-em-linha-final: 1rem;

}

.form-control-lg::file-selector-button {

&#x20; preenchimento: 0,5rem 1rem;

&#x20; margem: -0,5rem -1rem;

&#x20; -webkit-margin-end: 1rem;

&#x20; margem-em-linha-final: 1rem;

}



textarea.form-control {

&#x20; altura-mínima: calc(1.5em + 0.75rem + calc(var(--bs-border-width) \* 2));

}

textarea.form-control-sm {

&#x20; altura-mínima: calc(1.5em + 0.5rem + calc(var(--bs-border-width) \* 2));

}

textarea.form-control-lg {

&#x20; altura-mínima: calc(1.5em + 1rem + calc(var(--bs-border-width) \* 2));

}



.form-control-color {

&#x20; largura: 3rem;

&#x20; altura: calc(1.5em + 0.75rem + calc(var(--bs-border-width) \* 2));

&#x20; preenchimento: 0,375rem;

}

.form-control-color:not(:disabled):not(\[readonly]) {

&#x20; cursor: ponteiro;

}

.form-control-color::-moz-color-swatch {

&#x20; borda: 0 !importante;

&#x20; raio da borda: var(--bs-raio da borda);

}

.form-control-color::-webkit-color-swatch {

&#x20; borda: 0 !importante;

&#x20; raio da borda: var(--bs-raio da borda);

}

.form-control-color.form-control-sm {

&#x20; altura: calc(1.5em + 0.5rem + calc(var(--bs-border-width) \* 2));

}

.form-control-color.form-control-lg {

&#x20; altura: calc(1.5em + 1rem + calc(var(--bs-border-width) \* 2));

}



.form-select {

&#x20; --bs-form-select-bg-img: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='%23343a40' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='m2 5 6 6 6-6'/%3e%3c/svg%3e");

&#x20; exibir: bloco;

&#x20; largura: 100%;

&#x20; preenchimento: 0,375rem 2,25rem 0,375rem 0,75rem;

&#x20; tamanho da fonte: 1rem;

&#x20; peso da fonte: 400;

&#x20; altura da linha: 1,5;

&#x20; cor: var(--bs-body-color);

&#x20; cor de fundo: var(--bs-body-bg);

&#x20; background-image: var(--bs-form-select-bg-img), var(--bs-form-select-bg-icon, none);

&#x20; background-repeat: no-repeat;

&#x20; background-position: right 0.75rem center;

&#x20; tamanho do fundo: 16px 12px;

&#x20; borda: var(--bs-border-width) var sólido(--bs-border-color);

&#x20; raio da borda: var(--bs-raio da borda);

&#x20; transição: cor da borda 0,15s com suavização de entrada e saída, sombra da caixa 0,15s com suavização de entrada e saída;

&#x20; -webkit-appearance: nenhum;

&#x20; -moz-appearance: nenhuma;

&#x20; Aparência: nenhuma;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .form-select {

&#x20;   transição: nenhuma;

&#x20; }

}

.form-select:focus {

&#x20; cor da borda: #86b7fe;

&#x20; esboço: 0;

&#x20; box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

}

.form-select\[multiple], .form-select\[size]:not(\[size="1"]) {

&#x20; preenchimento à direita: 0,75rem;

&#x20; imagem de fundo: nenhuma;

}

.form-select:disabled {

&#x20; cor de fundo: var(--bs-secondary-bg);

}

.form-select:-moz-focusring {

&#x20; Cor: transparente;

&#x20; text-shadow: 0 0 0 var(--bs-body-color);

}



.form-select-sm {

&#x20; acolchoamento superior: 0,25rem;

&#x20; padding-bottom: 0.25rem;

&#x20; preenchimento à esquerda: 0,5rem;

&#x20; tamanho da fonte: 0,875rem;

&#x20; raio da borda: var(--bs-border-radius-sm);

}



.form-select-lg {

&#x20; padding-top: 0.5rem;

&#x20; padding-bottom: 0.5rem;

&#x20; preenchimento à esquerda: 1rem;

&#x20; tamanho da fonte: 1,25rem;

&#x20; raio da borda: var(-bs-border-radius-lg);

}



\[data-bs-theme=dark] .form-select {

&#x20; --bs-form-select-bg-img: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='%23adb5bd' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='m2 5 6 6 6-6'/%3e%3c/svg%3e");

}



.form-check {

&#x20; exibir: bloco;

&#x20; altura mínima: 1,5rem;

&#x20; preenchimento à esquerda: 1,5em;

&#x20; margem-inferior: 0,125rem;

}

.form-check .form-check-input {

&#x20; flutuar: esquerda;

&#x20; margem esquerda: -1,5em;

}



.form-check-reverse {

&#x20; preenchimento à direita: 1,5em;

&#x20; preenchimento-esquerdo: 0;

&#x20; alinhamento de texto: à direita;

}

.form-check-reverse .form-check-input {

&#x20; flutuar: direita;

&#x20; margem-direita: -1,5em;

&#x20; margem-esquerda: 0;

}



.form-check-input {

&#x20; --bs-form-check-bg: var(--bs-body-bg);

&#x20; largura: 1em;

&#x20; altura: 1em;

&#x20; margem superior: 0,25em;

&#x20; alinhamento vertical: superior;

&#x20; cor de fundo: var(--bs-form-check-bg);

&#x20; background-image: var(--bs-form-check-bg-image);

&#x20; background-repeat: no-repeat;

&#x20; posição de fundo: centro;

&#x20; tamanho de fundo: conter;

&#x20; borda: var(--bs-border-width) var sólido(--bs-border-color);

&#x20; -webkit-appearance: nenhum;

&#x20; -moz-appearance: nenhuma;

&#x20; Aparência: nenhuma;

&#x20; -webkit-print-color-adjust: exato;

&#x20; ajuste de cor: exato;

&#x20; ajuste de cor de impressão: exato;

}

.form-check-input\[type=checkbox] {

&#x20; raio-da-borda: 0,25em;

}

.form-check-input\[type=radio] {

&#x20; raio-da-borda: 50%;

}

.form-check-input:ativo {

&#x20; filtro: brilho (90%);

}

.form-check-input:focus {

&#x20; cor da borda: #86b7fe;

&#x20; esboço: 0;

&#x20; box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

}

.form-check-input:checked {

&#x20; cor de fundo: #0d6efd;

&#x20; cor da borda: #0d6efd;

}

.form-check-input:checked\[type=checkbox] {

&#x20; --bs-form-check-bg-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 20 20'%3e%3cpath fill='none' stroke='%23fff' stroke-linecap='round' stroke-linejoin='round' stroke-width='3' d='m6 10 3 3 6-6'/%3e%3c/svg%3e");

}

.form-check-input:checked\[type=radio] {

&#x20; --bs-form-check-bg-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='2' fill='%23fff'/%3e%3c/svg%3e");

}

.form-check-input\[type=checkbox]:indeterminate {

&#x20; cor de fundo: #0d6efd;

&#x20; cor da borda: #0d6efd;

&#x20; --bs-form-check-bg-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 20 20'%3e%3cpath fill='none' stroke='%23fff' stroke-linecap='round' stroke-linejoin='round' stroke-width='3' d='M6 10h8'/%3e%3c/svg%3e");

}

.form-check-input:disabled {

&#x20; eventos-ponteiro: nenhum;

&#x20; filtro: nenhum;

&#x20; opacidade: 0,5;

}

.form-check-input\[disabled] \~ .form-check-label, .form-check-input:disabled \~ .form-check-label {

&#x20; cursor: padrão;

&#x20; opacidade: 0,5;

}



.form-switch {

&#x20; preenchimento à esquerda: 2,5em;

}

.form-switch .form-check-input {

&#x20; --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='rgba%280, 0, 0, 0.25%29'/%3e%3c/svg%3e");

&#x20; largura: 2em;

&#x20; margem esquerda: -2,5em;

&#x20; background-image: var(--bs-form-switch-bg);

&#x20; background-position: centro esquerdo;

&#x20; raio-da-borda: 2em;

&#x20; transição: posição de fundo 0,15s entrada e saída suaves;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .form-switch .form-check-input {

&#x20;   transição: nenhuma;

&#x20; }

}

.form-switch .form-check-input:focus {

&#x20; --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='%2386b7fe'/%3e%3c/svg%3e");

}

.form-switch .form-check-input:checked {

&#x20; background-position: centro à direita;

&#x20; --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='%23fff'/%3e%3c/svg%3e");

}

.form-switch.form-check-reverse {

&#x20; padding-right: 2.5em;

&#x20; preenchimento-esquerdo: 0;

}

.form-switch.form-check-reverse .form-check-input {

&#x20; margem-direita: -2,5em;

&#x20; margem-esquerda: 0;

}



.form-check-inline {

&#x20; exibição: inline-block;

&#x20; margem-direita: 1rem;

}



.btn-check {

&#x20; posição: absoluta;

&#x20; recorte: rect(0, 0, 0, 0);

&#x20; eventos-ponteiro: nenhum;

}

.btn-check\[desativado] + .btn, .btn-check:desativado + .btn {

&#x20; eventos-ponteiro: nenhum;

&#x20; filtro: nenhum;

&#x20; opacidade: 0,65;

}



\[data-bs-theme=dark] .form-switch .form-check-input:not(:checked):not(:focus) {

&#x20; --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='rgba%28255, 255, 255, 0.25%29'/%3e%3c/svg%3e");

}



.form-range {

&#x20; largura: 100%;

&#x20; altura: 1,5rem;

&#x20; preenchimento: 0;

&#x20; cor de fundo: transparente;

&#x20; -webkit-appearance: nenhum;

&#x20; -moz-appearance: nenhuma;

&#x20; Aparência: nenhuma;

}

.form-range:focus {

&#x20; esboço: 0;

}

.form-range:focus::-webkit-slider-thumb {

&#x20; box-shadow: 0 0 0 1px #fff, 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

}

.form-range:focus::-moz-range-thumb {

&#x20; box-shadow: 0 0 0 1px #fff, 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

}

.form-range::-moz-focus-outer {

&#x20; borda: 0;

}

.form-range::-webkit-slider-thumb {

&#x20; largura: 1rem;

&#x20; altura: 1rem;

&#x20; margem superior: -0,25rem;

&#x20; cor de fundo: #0d6efd;

&#x20; borda: 0;

&#x20; raio-da-borda: 1rem;

&#x20; -webkit-transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;

&#x20; transição: cor de fundo 0,15s ease-in-out, cor da borda 0,15s ease-in-out, sombra da caixa 0,15s ease-in-out;

&#x20; -webkit-appearance: nenhum;

&#x20; Aparência: nenhuma;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .form-range::-webkit-slider-thumb {

&#x20;   -webkit-transition: nenhum;

&#x20;   transição: nenhuma;

&#x20; }

}

.form-range::-webkit-slider-thumb:active {

&#x20; cor de fundo: #b6d4fe;

}

.form-range::-webkit-slider-runnable-track {

&#x20; largura: 100%;

&#x20; altura: 0,5rem;

&#x20; Cor: transparente;

&#x20; cursor: ponteiro;

&#x20; cor de fundo: var(--bs-tertiary-bg);

&#x20; cor da borda: transparente;

&#x20; raio-da-borda: 1rem;

}

.form-range::-moz-range-thumb {

&#x20; largura: 1rem;

&#x20; altura: 1rem;

&#x20; cor de fundo: #0d6efd;

&#x20; borda: 0;

&#x20; raio-da-borda: 1rem;

&#x20; -moz-transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;

&#x20; transição: cor de fundo 0,15s ease-in-out, cor da borda 0,15s ease-in-out, sombra da caixa 0,15s ease-in-out;

&#x20; -moz-appearance: nenhuma;

&#x20; Aparência: nenhuma;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .form-range::-moz-range-thumb {

&#x20;   -moz-transição: nenhuma;

&#x20;   transição: nenhuma;

&#x20; }

}

.form-range::-moz-range-thumb:active {

&#x20; cor de fundo: #b6d4fe;

}

.form-range::-moz-range-track {

&#x20; largura: 100%;

&#x20; altura: 0,5rem;

&#x20; Cor: transparente;

&#x20; cursor: ponteiro;

&#x20; cor de fundo: var(--bs-tertiary-bg);

&#x20; cor da borda: transparente;

&#x20; raio-da-borda: 1rem;

}

.form-range:disabled {

&#x20; eventos-ponteiro: nenhum;

}

.form-range:disabled::-webkit-slider-thumb {

&#x20; cor de fundo: var(--bs-cor-secundária);

}

.form-range:disabled::-moz-range-thumb {

&#x20; cor de fundo: var(--bs-cor-secundária);

}



.form-floating {

&#x20; posição: relativa;

}

.form-floating > .form-control,

.form-floating > .form-control-plaintext,

.form-floating > .form-select {

&#x20; altura: calc(3.5rem + calc(var(--bs-border-width) \* 2));

&#x20; altura mínima: calc(3,5rem + calc(var(--bs-border-width) \* 2));

&#x20; altura da linha: 1,25;

}

.form-floating > rótulo {

&#x20; posição: absoluta;

&#x20; topo: 0;

&#x20; esquerda: 0;

&#x20; Índice z: 2;

&#x20; altura: 100%;

&#x20; preenchimento: 1rem 0,75rem;

&#x20; overflow: oculto;

&#x20; alinhamento de texto: início;

&#x20; estouro de texto: reticências;

&#x20; espaço em branco: nowrap;

&#x20; eventos-ponteiro: nenhum;

&#x20; borda: var(--bs-border-width) sólido transparente;

&#x20; origem-da-transformação: 0 0;

&#x20; transição: opacidade 0,1s suavização de entrada e saída, transformação 0,1s suavização de entrada e saída;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .form-floating > rótulo {

&#x20;   transição: nenhuma;

&#x20; }

}

.form-floating > .form-control,

.form-floating > .form-control-plaintext {

&#x20; preenchimento: 1rem 0,75rem;

}

.form-floating > .form-control::-moz-placeholder, .form-floating > .form-control-plaintext::-moz-placeholder {

&#x20; Cor: transparente;

}

.form-floating > .form-control::placeholder,

.form-floating > .form-control-plaintext::placeholder {

&#x20; Cor: transparente;

}

.form-floating > .form-control:not(:-moz-placeholder-shown), .form-floating > .form-control-plaintext:not(:-moz-placeholder-shown) {

&#x20; acolchoamento superior: 1,625rem;

&#x20; padding-bottom: 0.625rem;

}

.form-floating > .form-control:focus, .form-floating > .form-control:not(:placeholder-shown),

.form-floating > .form-control-plaintext:focus,

.form-floating > .form-control-plaintext:not(:placeholder-shown) {

&#x20; acolchoamento superior: 1,625rem;

&#x20; padding-bottom: 0.625rem;

}

.form-floating > .form-control:-webkit-autofill,

.form-floating > .form-control-plaintext:-webkit-autofill {

&#x20; acolchoamento superior: 1,625rem;

&#x20; padding-bottom: 0.625rem;

}

.form-floating > .form-select {

&#x20; acolchoamento superior: 1,625rem;

&#x20; padding-bottom: 0.625rem;

}

.form-floating > .form-control:not(:-moz-placeholder-shown) \~ label {

&#x20; cor: rgba(var(--bs-body-color-rgb), 0.65);

&#x20; transformar: escala(0,85) transladarY(-0,5rem) transladarX(0,15rem);

}

.form-floating > .form-control:focus \~ label,

.form-floating > .form-control:not(:placeholder-shown) \~ label,

.form-floating > .form-control-plaintext \~ label,

.form-floating > .form-select \~ label {

&#x20; cor: rgba(var(--bs-body-color-rgb), 0.65);

&#x20; transformar: escala(0,85) transladarY(-0,5rem) transladarX(0,15rem);

}

.form-floating > .form-control:not(:-moz-placeholder-shown) \~ label::after {

&#x20; posição: absoluta;

&#x20; inserção: 1rem 0,375rem;

&#x20; Índice z: -1;

&#x20; altura: 1,5em;

&#x20; contente: "";

&#x20; cor de fundo: var(--bs-body-bg);

&#x20; raio da borda: var(--bs-raio da borda);

}

.form-floating > .form-control:focus \~ label::after,

.form-floating > .form-control:not(:placeholder-shown) \~ label::after,

.form-floating > .form-control-plaintext \~ label::after,

.form-floating > .form-select \~ label::after {

&#x20; posição: absoluta;

&#x20; inserção: 1rem 0,375rem;

&#x20; Índice z: -1;

&#x20; altura: 1,5em;

&#x20; contente: "";

&#x20; cor de fundo: var(--bs-body-bg);

&#x20; raio da borda: var(--bs-raio da borda);

}

.form-floating > .form-control:-webkit-autofill \~ label {

&#x20; cor: rgba(var(--bs-body-color-rgb), 0.65);

&#x20; transformar: escala(0,85) transladarY(-0,5rem) transladarX(0,15rem);

}

.form-floating > .form-control-plaintext \~ label {

&#x20; largura-da-borda: var(--bs-border-width) 0;

}

.form-floating > :disabled \~ label {

&#x20; cor: #6c757d;

}

.form-floating > :disabled \~ label::after {

&#x20; cor de fundo: var(--bs-secondary-bg);

}



.grupo-de-entrada {

&#x20; posição: relativa;

&#x20; Exibir: flexível;

&#x20; flex-wrap: envolver;

&#x20; alinhamento-itens: esticar;

&#x20; largura: 100%;

}

.input-group > .form-control,

.input-group > .form-select,

.input-group > .form-floating {

&#x20; posição: relativa;

&#x20; flex: 1 1 auto;

&#x20; largura: 1%;

&#x20; largura mínima: 0;

}

.input-group > .form-control:focus,

.input-group > .form-select:focus,

.input-group > .form-floating:focus-within {

&#x20; Índice z: 5;

}

.input-group .btn {

&#x20; posição: relativa;

&#x20; Índice z: 2;

}

.input-group .btn:focus {

&#x20; Índice z: 5;

}



.input-group-text {

&#x20; Exibir: flexível;

&#x20; alinhamento-itens: centro;

&#x20; preenchimento: 0,375rem 0,75rem;

&#x20; tamanho da fonte: 1rem;

&#x20; peso da fonte: 400;

&#x20; altura da linha: 1,5;

&#x20; cor: var(--bs-body-color);

&#x20; alinhamento do texto: centralizado;

&#x20; espaço em branco: nowrap;

&#x20; cor de fundo: var(--bs-tertiary-bg);

&#x20; borda: var(--bs-border-width) var sólido(--bs-border-color);

&#x20; raio da borda: var(--bs-raio da borda);

}



.input-group-lg > .form-control,

.input-group-lg > .form-select,

.input-group-lg > .input-group-text,

.input-group-lg > .btn {

&#x20; preenchimento: 0,5rem 1rem;

&#x20; tamanho da fonte: 1,25rem;

&#x20; raio da borda: var(-bs-border-radius-lg);

}



.input-group-sm > .form-control,

.input-group-sm > .form-select,

.input-group-sm > .input-group-text,

.input-group-sm > .btn {

&#x20; preenchimento: 0,25rem 0,5rem;

&#x20; tamanho da fonte: 0,875rem;

&#x20; raio da borda: var(--bs-border-radius-sm);

}



.input-group-lg > .form-select,

.input-group-sm > .form-select {

&#x20; padding-right: 3rem;

}



.input-group:not(.has-validation) > :not(:last-child):not(.dropdown-toggle):not(.dropdown-menu):not(.form-floating),

.input-group:not(.has-validation) > .dropdown-toggle:nth-last-child(n+3),

.input-group:not(.has-validation) > .form-floating:not(:last-child) > .form-control,

.input-group:not(.has-validation) > .form-floating:not(:last-child) > .form-select {

&#x20; raio-superior-direito-da-borda: 0;

&#x20; raio-inferior-direito-da-borda: 0;

}

.input-group.has-validation > :nth-last-child(n+3):not(.dropdown-toggle):not(.dropdown-menu):not(.form-floating),

.input-group.has-validation > .dropdown-toggle:nth-last-child(n+4),

.input-group.has-validation > .form-floating:nth-last-child(n+3) > .form-control,

.input-group.has-validation > .form-floating:nth-last-child(n+3) > .form-select {

&#x20; raio-superior-direito-da-borda: 0;

&#x20; raio-inferior-direito-da-borda: 0;

}

.input-group > :not(:first-child):not(.dropdown-menu):not(.valid-tooltip):not(.valid-feedback):not(.invalid-tooltip):not(.invalid-feedback) {

&#x20; margem-esquerda: calc(var(--bs-border-width) \* -1);

&#x20; raio-superior-esquerdo-da-borda: 0;

&#x20; raio-da-borda-inferior-esquerda: 0;

}

.input-group > .form-floating:not(:first-child) > .form-control,

.input-group > .form-floating:not(:first-child) > .form-select {

&#x20; raio-superior-esquerdo-da-borda: 0;

&#x20; raio-da-borda-inferior-esquerda: 0;

}



.feedback-válido {

&#x20; exibir: nenhum;

&#x20; largura: 100%;

&#x20; margem superior: 0,25rem;

&#x20; tamanho da fonte: 0,875em;

&#x20; cor: var(--bs-form-valid-color);

}



.dica-de-ferramenta-válida {

&#x20; posição: absoluta;

&#x20; topo: 100%;

&#x20; Índice z: 5;

&#x20; exibir: nenhum;

&#x20; largura máxima: 100%;

&#x20; preenchimento: 0,25rem 0,5rem;

&#x20; margem superior: 0,1rem;

&#x20; tamanho da fonte: 0,875rem;

&#x20; cor: #fff;

&#x20; cor de fundo: var(--bs-success);

&#x20; raio da borda: var(--bs-raio da borda);

}



.foi-validado :válido \~ .feedback-válido,

.foi-validado :válido \~ .dica-de-ferramenta-válida,

.é-válido \~ .feedback-válido,

.é-válido \~ .dica-de-ferramenta-válida {

&#x20; exibir: bloco;

}



.foi-validado .controle-formulário:válido, .controle-formulário.é-válido {

&#x20; cor-da-borda: var(--bs-form-valid-border-color);

&#x20; padding-right: calc(1.5em + 0.75rem);

&#x20; background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%23198754' d='M2.3 6.73.6 4.53c-.4-1.04.46-1.4 1.1-.8l1.1 1.4 3.4-3.8c.6-.63 1.6-.27 1.2.7l-4 4.6c-.43.5-.8.4-1.1.1z'/%3e%3c/svg%3e");

&#x20; background-repeat: no-repeat;

&#x20; background-position: right calc(0.375em + 0.1875rem) center;

&#x20; background-size: calc(0.75em + 0.375rem) calc(0.75em + 0.375rem);

}

.was-validated .form-control:valid:focus, .form-control.is-valid:focus {

&#x20; cor-da-borda: var(--bs-form-valid-border-color);

&#x20; box-shadow: 0 0 0 0.25rem rgba(var(--bs-success-rgb), 0.25);

}



.was-validated textarea.form-control:valid, textarea.form-control.is-valid {

&#x20; padding-right: calc(1.5em + 0.75rem);

&#x20; background-position: top calc(0.375em + 0.1875rem) right calc(0.375em + 0.1875rem);

}



.foi-validado .form-select:válido, .form-select.é-válido {

&#x20; cor-da-borda: var(--bs-form-valid-border-color);

}

.was-validated .form-select:valid:not(\[multiple]):not(\[size]), .was-validated .form-select:valid:not(\[multiple])\[size="1"], .form-select.is-valid:not(\[multiple]):not(\[size]), .form-select.is-valid:not(\[multiple])\[size="1"] {

&#x20; --bs-form-select-bg-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%23198754' d='M2.3 6.73.6 4.53c-.4-1.04.46-1.4 1.1-.8l1.1 1.4 3.4-3.8c.6-.63 1.6-.27 1.2.7l-4 4.6c-.43.5-.8.4-1.1.1z'/%3e%3c/svg%3e");

&#x20; padding-right: 4.125rem;

&#x20; background-position: right 0.75rem center, center right 2.25rem;

&#x20; background-size: 16px 12px, calc(0.75em + 0.375rem) calc(0.75em + 0.375rem);

}

.foi-validado .form-select:válido:foco, .form-select.é-válido:foco {

&#x20; cor-da-borda: var(--bs-form-valid-border-color);

&#x20; box-shadow: 0 0 0 0.25rem rgba(var(--bs-success-rgb), 0.25);

}



.foi-validado .cor-do-controle-do-formulário:válido, .cor-do-controle-do-formulário.é-válido {

&#x20; largura: calc(3rem + calc(1.5em + 0.75rem));

}



.foi-validado .form-check-input:válido, .form-check-input.é-válido {

&#x20; cor-da-borda: var(--bs-form-valid-border-color);

}

.was-validated .form-check-input:valid:checked, .form-check-input.is-valid:checked {

&#x20; cor de fundo: var(--bs-form-valid-color);

}

.was-validated .form-check-input:valid:focus, .form-check-input.is-valid:focus {

&#x20; box-shadow: 0 0 0 0.25rem rgba(var(--bs-success-rgb), 0.25);

}

.was-validated .form-check-input:valid \~ .form-check-label, .form-check-input.is-valid \~ .form-check-label {

&#x20; cor: var(--bs-form-valid-color);

}



.form-check-inline .form-check-input \~ .valid-feedback {

&#x20; margem esquerda: 0,5em;

}



.was-validated .input-group > .form-control:not(:focus):valid, .input-group > .form-control:not(:focus).is-valid,

.was-validated .input-group > .form-select:not(:focus):valid,

.input-group > .form-select:not(:focus).is-valid,

.was-validated .input-group > .form-floating:not(:focus-within):valid,

.input-group > .form-floating:not(:focus-within).is-valid {

&#x20; Índice z: 3;

}



.feedback inválido {

&#x20; exibir: nenhum;

&#x20; largura: 100%;

&#x20; margem superior: 0,25rem;

&#x20; tamanho da fonte: 0,875em;

&#x20; cor: var(--bs-form-invalid-color);

}



.invalid-tooltip {

&#x20; posição: absoluta;

&#x20; topo: 100%;

&#x20; Índice z: 5;

&#x20; exibir: nenhum;

&#x20; largura máxima: 100%;

&#x20; preenchimento: 0,25rem 0,5rem;

&#x20; margem superior: 0,1rem;

&#x20; tamanho da fonte: 0,875rem;

&#x20; cor: #fff;

&#x20; cor de fundo: var(--bs-danger);

&#x20; raio da borda: var(--bs-raio da borda);

}



.foi-validado :inválido \~ .feedback-inválido,

.foi-validado :inválido \~ .dica-de-ferramenta-inválida,

.é-inválido \~ .feedback-inválido,

.é-inválido \~ .dica-inválida {

&#x20; exibir: bloco;

}



.foi-validado .controle-formulário:inválido, .controle-formulário.é-inválido {

&#x20; cor-da-borda: var(--bs-form-invalid-border-color);

&#x20; padding-right: calc(1.5em + 0.75rem);

&#x20; background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 12 12' width='12' height='12' fill='none' stroke='%23dc3545'%3e%3ccircle cx='6' cy='6' r='4.5'/%3e%3cpath stroke-linejoin='round' d='M5.8 3.6h.4L6 6.5z'/%3e%3ccircle cx='6' cy='8.2' r='.6' fill='%23dc3545' stroke='none'/%3e%3c/svg%3e");

&#x20; background-repeat: no-repeat;

&#x20; background-position: right calc(0.375em + 0.1875rem) center;

&#x20; background-size: calc(0.75em + 0.375rem) calc(0.75em + 0.375rem);

}

.foi-validado .controle-formulário:inválido:foco, .controle-formulário.é-inválido:foco {

&#x20; cor-da-borda: var(--bs-form-invalid-border-color);

&#x20; sombra da caixa: 0 0 0 0,25rem rgba(var(--bs-danger-rgb), 0,25);

}



.was-validated textarea.form-control:invalid, textarea.form-control.is-invalid {

&#x20; padding-right: calc(1.5em + 0.75rem);

&#x20; background-position: top calc(0.375em + 0.1875rem) right calc(0.375em + 0.1875rem);

}



.foi-validado .form-select:inválido, .form-select.é-inválido {

&#x20; cor-da-borda: var(--bs-form-invalid-border-color);

}

.was-validated .form-select:invalid:not(\[multiple]):not(\[size]), .was-validated .form-select:invalid:not(\[multiple])\[size="1"], .form-select.is-invalid:not(\[multiple]):not(\[size]), .form-select.is-invalid:not(\[multiple])\[size="1"] {

&#x20; --bs-form-select-bg-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 12 12' width='12' height='12' fill='none' stroke='%23dc3545'%3e%3ccircle cx='6' cy='6' r='4.5'/%3e%3cpath stroke-linejoin='round' d='M5.8 3.6h.4L6 6.5z'/%3e%3ccircle cx='6' cy='8.2' r='.6' fill='%23dc3545' stroke='none'/%3e%3c/svg%3e");

&#x20; padding-right: 4.125rem;

&#x20; background-position: right 0.75rem center, center right 2.25rem;

&#x20; background-size: 16px 12px, calc(0.75em + 0.375rem) calc(0.75em + 0.375rem);

}

.foi-validado .form-select:inválido:foco, .form-select.é-inválido:foco {

&#x20; cor-da-borda: var(--bs-form-invalid-border-color);

&#x20; sombra da caixa: 0 0 0 0,25rem rgba(var(--bs-danger-rgb), 0,25);

}



.foi-validado .cor-controle-formulário:inválido, .cor-controle-formulário.é-inválido {

&#x20; largura: calc(3rem + calc(1.5em + 0.75rem));

}



.foi-validado .form-check-input:inválido, .form-check-input.é-inválido {

&#x20; cor-da-borda: var(--bs-form-invalid-border-color);

}

.foi-validado .form-check-input:inválido:marcado, .form-check-input.é-inválido:marcado {

&#x20; cor de fundo: var(--bs-form-invalid-color);

}

.foi-validado .form-check-input:inválido:foco, .form-check-input.é-inválido:foco {

&#x20; sombra da caixa: 0 0 0 0,25rem rgba(var(--bs-danger-rgb), 0,25);

}

.was-validated .form-check-input:invalid \~ .form-check-label, .form-check-input.is-invalid \~ .form-check-label {

&#x20; cor: var(--bs-form-invalid-color);

}



.form-check-inline .form-check-input \~ .invalid-feedback {

&#x20; margem esquerda: 0,5em;

}



.was-validated .input-group > .form-control:not(:focus):invalid, .input-group > .form-control:not(:focus).is-invalid,

.was-validated .input-group > .form-select:not(:focus):invalid,

.input-group > .form-select:not(:focus).is-invalid,

.was-validated .input-group > .form-floating:not(:focus-within):invalid,

.input-group > .form-floating:not(:focus-within).is-invalid {

&#x20; Índice z: 4;

}



.btn {

&#x20; --bs-btn-padding-x: 0.75rem;

&#x20; --bs-btn-padding-y: 0.375rem;

&#x20; --bs-btn-font-family: ;

&#x20; --bs-btn-font-size: 1rem;

&#x20; --bs-btn-font-weight: 400;

&#x20; --bs-btn-line-height: 1.5;

&#x20; --bs-btn-color: var(--bs-body-color);

&#x20; --bs-btn-bg: transparente;

&#x20; --bs-btn-border-width: var(--bs-border-width);

&#x20; --bs-btn-border-color: transparente;

&#x20; --bs-btn-raio da borda: var(--bs-raio da borda);

&#x20; --bs-btn-hover-border-color: transparente;

&#x20; --bs-btn-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075);

&#x20; --bs-btn-disabled-opacity: 0.65;

&#x20; --bs-btn-focus-box-shadow: 0 0 0 0.25rem rgba(var(--bs-btn-focus-shadow-rgb), .5);

&#x20; exibição: inline-block;

&#x20; preenchimento: var(--bs-btn-padding-y) var(--bs-btn-padding-x);

&#x20; família-fonte: var(--bs-btn-font-family);

&#x20; tamanho da fonte: var(--bs-btn-tamanho da fonte);

&#x20; peso-da-fonte: var(--bs-btn-font-weight);

&#x20; altura-da-linha: var(--bs-btn-altura-da-linha);

&#x20; cor: var(--bs-btn-color);

&#x20; alinhamento do texto: centralizado;

&#x20; decoração de texto: nenhuma;

&#x20; alinhamento vertical: meio;

&#x20; cursor: ponteiro;

&#x20; -webkit-user-select: nenhum;

&#x20; -moz-user-select: nenhum;

&#x20; seleção do usuário: nenhuma;

&#x20; borda: var(--bs-btn-border-width) sólido var(--bs-btn-border-color);

&#x20; raio da borda: var(--bs-btn-raio da borda);

&#x20; cor de fundo: var(--bs-btn-bg);

&#x20; transição: cor 0,15s ease-in-out, cor de fundo 0,15s ease-in-out, cor da borda 0,15s ease-in-out, sombra da caixa 0,15s ease-in-out;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .btn {

&#x20;   transição: nenhuma;

&#x20; }

}

.btn:hover {

&#x20; cor: var(--bs-btn-hover-color);

&#x20; cor de fundo: var(--bs-btn-hover-bg);

&#x20; cor-da-borda: var(--bs-btn-hover-border-color);

}

.btn-check + .btn:hover {

&#x20; cor: var(--bs-btn-color);

&#x20; cor de fundo: var(--bs-btn-bg);

&#x20; cor-da-borda: var(--bs-btn-border-color);

}

.btn:focus-visible {

&#x20; cor: var(--bs-btn-hover-color);

&#x20; cor de fundo: var(--bs-btn-hover-bg);

&#x20; cor-da-borda: var(--bs-btn-hover-border-color);

&#x20; esboço: 0;

&#x20; box-shadow: var(--bs-btn-focus-box-shadow);

}

.btn-check:focus-visible + .btn {

&#x20; cor-da-borda: var(--bs-btn-hover-border-color);

&#x20; esboço: 0;

&#x20; box-shadow: var(--bs-btn-focus-box-shadow);

}

.btn-check:checked + .btn, :not(.btn-check) + .btn:active, .btn:first-child:active, .btn.active, .btn.show {

&#x20; cor: var(--bs-btn-active-color);

&#x20; cor de fundo: var(--bs-btn-active-bg);

&#x20; cor-da-borda: var(--bs-btn-active-border-color);

}

.btn-check:checked + .btn:focus-visible, :not(.btn-check) + .btn:active:focus-visible, .btn:first-child:active:focus-visible, .btn.active:focus-visible, .btn.show:focus-visible {

&#x20; box-shadow: var(--bs-btn-focus-box-shadow);

}

.btn:disabled, .btn.disabled, fieldset:disabled .btn {

&#x20; cor: var(--bs-btn-disabled-color);

&#x20; eventos-ponteiro: nenhum;

&#x20; cor de fundo: var(--bs-btn-disabled-bg);

&#x20; cor-da-borda: var(--bs-btn-disabled-border-color);

&#x20; opacidade: var(--bs-btn-disabled-opacity);

}



.btn-primary {

&#x20; --bs-btn-color: #fff;

&#x20; --bs-btn-bg: #0d6efd;

&#x20; --bs-btn-border-color: #0d6efd;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #0b5ed7;

&#x20; --bs-btn-hover-border-color: #0a58ca;

&#x20; --bs-btn-focus-shadow-rgb: 49, 132, 253;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #0a58ca;

&#x20; --bs-btn-active-border-color: #0a53be;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #fff;

&#x20; --bs-btn-disabled-bg: #0d6efd;

&#x20; --bs-btn-disabled-border-color: #0d6efd;

}



.btn-secondary {

&#x20; --bs-btn-color: #fff;

&#x20; --bs-btn-bg: #6c757d;

&#x20; --bs-btn-border-color: #6c757d;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #5c636a;

&#x20; --bs-btn-hover-border-color: #565e64;

&#x20; --bs-btn-focus-shadow-rgb: 130, 138, 145;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #565e64;

&#x20; --bs-btn-active-border-color: #51585e;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #fff;

&#x20; --bs-btn-disabled-bg: #6c757d;

&#x20; --bs-btn-disabled-border-color: #6c757d;

}



.btn-sucesso {

&#x20; --bs-btn-color: #fff;

&#x20; --bs-btn-bg: #198754;

&#x20; --bs-btn-border-color: #198754;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #157347;

&#x20; --bs-btn-hover-border-color: #146c43;

&#x20; --bs-btn-focus-shadow-rgb: 60, 153, 110;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #146c43;

&#x20; --bs-btn-active-border-color: #13653f;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #fff;

&#x20; --bs-btn-disabled-bg: #198754;

&#x20; --bs-btn-disabled-border-color: #198754;

}



.btn-info {

&#x20; --bs-btn-color: #000;

&#x20; --bs-btn-bg: #0dcaf0;

&#x20; --bs-btn-border-color: #0dcaf0;

&#x20; --bs-btn-hover-color: #000;

&#x20; --bs-btn-hover-bg: #31d2f2;

&#x20; --bs-btn-hover-border-color: #25cff2;

&#x20; --bs-btn-focus-shadow-rgb: 11, 172, 204;

&#x20; --bs-btn-active-color: #000;

&#x20; --bs-btn-active-bg: #3dd5f3;

&#x20; --bs-btn-active-border-color: #25cff2;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #000;

&#x20; --bs-btn-disabled-bg: #0dcaf0;

&#x20; --bs-btn-disabled-border-color: #0dcaf0;

}



.btn-warning {

&#x20; --bs-btn-color: #000;

&#x20; --bs-btn-bg: #ffc107;

&#x20; --bs-btn-border-color: #ffc107;

&#x20; --bs-btn-hover-color: #000;

&#x20; --bs-btn-hover-bg: #ffca2c;

&#x20; --bs-btn-hover-border-color: #ffc720;

&#x20; --bs-btn-focus-shadow-rgb: 217, 164, 6;

&#x20; --bs-btn-active-color: #000;

&#x20; --bs-btn-active-bg: #ffcd39;

&#x20; --bs-btn-active-border-color: #ffc720;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #000;

&#x20; --bs-btn-disabled-bg: #ffc107;

&#x20; --bs-btn-disabled-border-color: #ffc107;

}



.btn-danger {

&#x20; --bs-btn-color: #fff;

&#x20; --bs-btn-bg: #dc3545;

&#x20; --bs-btn-border-color: #dc3545;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #bb2d3b;

&#x20; --bs-btn-hover-border-color: #b02a37;

&#x20; --bs-btn-focus-shadow-rgb: 225, 83, 97;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #b02a37;

&#x20; --bs-btn-active-border-color: #a52834;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #fff;

&#x20; --bs-btn-disabled-bg: #dc3545;

&#x20; --bs-btn-disabled-border-color: #dc3545;

}



.btn-light {

&#x20; --bs-btn-color: #000;

&#x20; --bs-btn-bg: #f8f9fa;

&#x20; --bs-btn-border-color: #f8f9fa;

&#x20; --bs-btn-hover-color: #000;

&#x20; --bs-btn-hover-bg: #d3d4d5;

&#x20; --bs-btn-hover-border-color: #c6c7c8;

&#x20; --bs-btn-focus-shadow-rgb: 211, 212, 213;

&#x20; --bs-btn-active-color: #000;

&#x20; --bs-btn-active-bg: #c6c7c8;

&#x20; --bs-btn-active-border-color: #babbbc;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #000;

&#x20; --bs-btn-disabled-bg: #f8f9fa;

&#x20; --bs-btn-disabled-border-color: #f8f9fa;

}



.btn-dark {

&#x20; --bs-btn-color: #fff;

&#x20; --bs-btn-bg: #212529;

&#x20; --bs-btn-border-color: #212529;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #424649;

&#x20; --bs-btn-hover-border-color: #373b3e;

&#x20; --bs-btn-focus-shadow-rgb: 66, 70, 73;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #4d5154;

&#x20; --bs-btn-active-border-color: #373b3e;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #fff;

&#x20; --bs-btn-disabled-bg: #212529;

&#x20; --bs-btn-disabled-border-color: #212529;

}



.btn-outline-primary {

&#x20; --bs-btn-color: #0d6efd;

&#x20; --bs-btn-border-color: #0d6efd;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #0d6efd;

&#x20; --bs-btn-hover-border-color: #0d6efd;

&#x20; --bs-btn-focus-shadow-rgb: 13, 110, 253;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #0d6efd;

&#x20; --bs-btn-active-border-color: #0d6efd;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #0d6efd;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #0d6efd;

&#x20; --bs-gradient: nenhum;

}



.btn-outline-secondary {

&#x20; --bs-btn-color: #6c757d;

&#x20; --bs-btn-border-color: #6c757d;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #6c757d;

&#x20; --bs-btn-hover-border-color: #6c757d;

&#x20; --bs-btn-focus-shadow-rgb: 108, 117, 125;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #6c757d;

&#x20; --bs-btn-active-border-color: #6c757d;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #6c757d;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #6c757d;

&#x20; --bs-gradient: nenhum;

}



.btn-outline-success {

&#x20; --bs-btn-color: #198754;

&#x20; --bs-btn-border-color: #198754;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #198754;

&#x20; --bs-btn-hover-border-color: #198754;

&#x20; --bs-btn-focus-shadow-rgb: 25, 135, 84;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #198754;

&#x20; --bs-btn-active-border-color: #198754;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #198754;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #198754;

&#x20; --bs-gradient: nenhum;

}



.btn-outline-info {

&#x20; --bs-btn-color: #0dcaf0;

&#x20; --bs-btn-border-color: #0dcaf0;

&#x20; --bs-btn-hover-color: #000;

&#x20; --bs-btn-hover-bg: #0dcaf0;

&#x20; --bs-btn-hover-border-color: #0dcaf0;

&#x20; --bs-btn-focus-shadow-rgb: 13, 202, 240;

&#x20; --bs-btn-active-color: #000;

&#x20; --bs-btn-active-bg: #0dcaf0;

&#x20; --bs-btn-active-border-color: #0dcaf0;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #0dcaf0;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #0dcaf0;

&#x20; --bs-gradient: nenhum;

}



.btn-outline-warning {

&#x20; --bs-btn-color: #ffc107;

&#x20; --bs-btn-border-color: #ffc107;

&#x20; --bs-btn-hover-color: #000;

&#x20; --bs-btn-hover-bg: #ffc107;

&#x20; --bs-btn-hover-border-color: #ffc107;

&#x20; --bs-btn-focus-shadow-rgb: 255, 193, 7;

&#x20; --bs-btn-active-color: #000;

&#x20; --bs-btn-active-bg: #ffc107;

&#x20; --bs-btn-active-border-color: #ffc107;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #ffc107;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #ffc107;

&#x20; --bs-gradient: nenhum;

}



.btn-outline-danger {

&#x20; --bs-btn-color: #dc3545;

&#x20; --bs-btn-border-color: #dc3545;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #dc3545;

&#x20; --bs-btn-hover-border-color: #dc3545;

&#x20; --bs-btn-focus-shadow-rgb: 220, 53, 69;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #dc3545;

&#x20; --bs-btn-active-border-color: #dc3545;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #dc3545;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #dc3545;

&#x20; --bs-gradient: nenhum;

}



.btn-outline-light {

&#x20; --bs-btn-color: #f8f9fa;

&#x20; --bs-btn-border-color: #f8f9fa;

&#x20; --bs-btn-hover-color: #000;

&#x20; --bs-btn-hover-bg: #f8f9fa;

&#x20; --bs-btn-hover-border-color: #f8f9fa;

&#x20; --bs-btn-focus-shadow-rgb: 248, 249, 250;

&#x20; --bs-btn-active-color: #000;

&#x20; --bs-btn-active-bg: #f8f9fa;

&#x20; --bs-btn-active-border-color: #f8f9fa;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #f8f9fa;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #f8f9fa;

&#x20; --bs-gradient: nenhum;

}



.btn-outline-dark {

&#x20; --bs-btn-color: #212529;

&#x20; --bs-btn-border-color: #212529;

&#x20; --bs-btn-hover-color: #fff;

&#x20; --bs-btn-hover-bg: #212529;

&#x20; --bs-btn-hover-border-color: #212529;

&#x20; --bs-btn-focus-shadow-rgb: 33, 37, 41;

&#x20; --bs-btn-active-color: #fff;

&#x20; --bs-btn-active-bg: #212529;

&#x20; --bs-btn-active-border-color: #212529;

&#x20; --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

&#x20; --bs-btn-disabled-color: #212529;

&#x20; --bs-btn-disabled-bg: transparente;

&#x20; --bs-btn-disabled-border-color: #212529;

&#x20; --bs-gradient: nenhum;

}



.btn-link {

&#x20; --bs-btn-font-weight: 400;

&#x20; --bs-btn-color: var(--bs-link-color);

&#x20; --bs-btn-bg: transparente;

&#x20; --bs-btn-border-color: transparente;

&#x20; --bs-btn-hover-color: var(--bs-link-hover-color);

&#x20; --bs-btn-hover-border-color: transparente;

&#x20; --bs-btn-active-color: var(--bs-link-hover-color);

&#x20; --bs-btn-active-border-color: transparente;

&#x20; --bs-btn-disabled-color: #6c757d;

&#x20; --bs-btn-disabled-border-color: transparente;

&#x20; --bs-btn-box-shadow: 0 0 0 #000;

&#x20; --bs-btn-focus-shadow-rgb: 49, 132, 253;

&#x20; decoração de texto: sublinhado;

}

.btn-link:focus-visible {

&#x20; cor: var(--bs-btn-color);

}

.btn-link:hover {

&#x20; cor: var(--bs-btn-hover-color);

}



.btn-lg, .btn-group-lg > .btn {

&#x20; --bs-btn-padding-y: 0.5rem;

&#x20; --bs-btn-padding-x: 1rem;

&#x20; --bs-btn-font-size: 1.25rem;

&#x20; --bs-btn-border-radius: var(--bs-border-radius-lg);

}



.btn-sm, .btn-group-sm > .btn {

&#x20; --bs-btn-padding-y: 0.25rem;

&#x20; --bs-btn-padding-x: 0.5rem;

&#x20; --bs-btn-font-size: 0.875rem;

&#x20; --bs-btn-raio da borda: var(--bs-raio da borda-sm);

}



.desaparecer {

&#x20; transição: opacidade 0,15s linear;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .desaparecer {

&#x20;   transição: nenhuma;

&#x20; }

}

.fade:não(.show) {

&#x20; opacidade: 0;

}



.collapse:not(.show) {

&#x20; exibir: nenhum;

}



.colapsando {

&#x20; altura: 0;

&#x20; overflow: oculto;

&#x20; transição: altura 0,35s de facilidade;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .colapsando {

&#x20;   transição: nenhuma;

&#x20; }

}

.colapsando.colapso-horizontal {

&#x20; largura: 0;

&#x20; altura: automática;

&#x20; transição: largura 0,35s de facilidade;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .colapsando.colapso-horizontal {

&#x20;   transição: nenhuma;

&#x20; }

}



.dropup,

.dropend,

.suspenso,

.dropstart,

.dropup-center,

.dropdown-center {

&#x20; posição: relativa;

}



.dropdown-toggle {

&#x20; espaço em branco: nowrap;

}

.dropdown-toggle::after {

&#x20; exibição: inline-block;

&#x20; margem esquerda: 0,255em;

&#x20; alinhamento vertical: 0,255em;

&#x20; contente: "";

&#x20; borda superior: 0,3em sólida;

&#x20; borda-direita: 0,3em sólida transparente;

&#x20; borda-inferior: 0;

&#x20; borda esquerda: 0,3em sólida transparente;

}

.dropdown-toggle:empty::after {

&#x20; margem-esquerda: 0;

}



.dropdown-menu {

&#x20; --bs-dropdown-zindex: 1000;

&#x20; --bs-dropdown-min-width: 10rem;

&#x20; --bs-dropdown-padding-x: 0;

&#x20; --bs-dropdown-padding-y: 0.5rem;

&#x20; --bs-dropdown-spacer: 0.125rem;

&#x20; --bs-dropdown-font-size: 1rem;

&#x20; --bs-dropdown-color: var(--bs-body-color);

&#x20; --bs-dropdown-bg: var(--bs-body-bg);

&#x20; --bs-dropdown-border-color: var(--bs-border-color-translucent);

&#x20; --bs-dropdown-border-radius: var(--bs-border-radius);

&#x20; --bs-dropdown-border-width: var(--bs-border-width);

&#x20; --bs-dropdown-inner-border-radius: calc(var(--bs-border-radius) - var(--bs-border-width));

&#x20; --bs-dropdown-divider-bg: var(--bs-border-color-translucent);

&#x20; --bs-dropdown-divider-margin-y: 0.5rem;

&#x20; --bs-dropdown-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);

&#x20; --bs-dropdown-link-color: var(--bs-body-color);

&#x20; --bs-dropdown-link-hover-color: var(--bs-body-color);

&#x20; --bs-dropdown-link-hover-bg: var(--bs-tertiary-bg);

&#x20; --bs-dropdown-link-active-color: #fff;

&#x20; --bs-dropdown-link-active-bg: #0d6efd;

&#x20; --bs-dropdown-link-disabled-color: var(--bs-tertiary-color);

&#x20; --bs-dropdown-item-padding-x: 1rem;

&#x20; --bs-dropdown-item-padding-y: 0.25rem;

&#x20; --bs-dropdown-header-color: #6c757d;

&#x20; --bs-dropdown-header-padding-x: 1rem;

&#x20; --bs-dropdown-header-padding-y: 0.5rem;

&#x20; posição: absoluta;

&#x20; z-index: var(--bs-dropdown-zindex);

&#x20; exibir: nenhum;

&#x20; largura-mínima: var(--bs-dropdown-min-width);

&#x20; preenchimento: var(--bs-dropdown-padding-y) var(--bs-dropdown-padding-x);

&#x20; margem: 0;

&#x20; tamanho-da-fonte: var(--bs-dropdown-font-size);

&#x20; cor: var(--bs-dropdown-color);

&#x20; alinhamento de texto: esquerda;

&#x20; estilo de lista: nenhum;

&#x20; cor de fundo: var(--bs-dropdown-bg);

&#x20; background-clip: padding-box;

&#x20; borda: var(--bs-dropdown-border-width) sólida var(--bs-dropdown-border-color);

&#x20; raio-da-borda: var(--bs-dropdown-border-radius);

}

.dropdown-menu\[data-bs-popper] {

&#x20; topo: 100%;

&#x20; esquerda: 0;

&#x20; margem-superior: var(--bs-dropdown-spacer);

}



.dropdown-menu-start {

&#x20; --bs-position: início;

}

.dropdown-menu-start\[data-bs-popper] {

&#x20; direita: automático;

&#x20; esquerda: 0;

}



.dropdown-menu-end {

&#x20; --bs-position: fim;

}

.dropdown-menu-end\[data-bs-popper] {

&#x20; direita: 0;

&#x20; esquerda: automático;

}



@media (min-width: 576px) {

&#x20; .dropdown-menu-sm-start {

&#x20;   --bs-position: início;

&#x20; }

&#x20; .dropdown-menu-sm-start\[data-bs-popper] {

&#x20;   direita: automático;

&#x20;   esquerda: 0;

&#x20; }

&#x20; .dropdown-menu-sm-end {

&#x20;   --bs-position: fim;

&#x20; }

&#x20; .dropdown-menu-sm-end\[data-bs-popper] {

&#x20;   direita: 0;

&#x20;   esquerda: automático;

&#x20; }

}

@media (min-width: 768px) {

&#x20; .dropdown-menu-md-start {

&#x20;   --bs-position: início;

&#x20; }

&#x20; .dropdown-menu-md-start\[data-bs-popper] {

&#x20;   direita: automático;

&#x20;   esquerda: 0;

&#x20; }

&#x20; .dropdown-menu-md-end {

&#x20;   --bs-position: fim;

&#x20; }

&#x20; .dropdown-menu-md-end\[data-bs-popper] {

&#x20;   direita: 0;

&#x20;   esquerda: automático;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .dropdown-menu-lg-start {

&#x20;   --bs-position: início;

&#x20; }

&#x20; .dropdown-menu-lg-start\[data-bs-popper] {

&#x20;   direita: automático;

&#x20;   esquerda: 0;

&#x20; }

&#x20; .dropdown-menu-lg-end {

&#x20;   --bs-position: fim;

&#x20; }

&#x20; .dropdown-menu-lg-end\[data-bs-popper] {

&#x20;   direita: 0;

&#x20;   esquerda: automático;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .dropdown-menu-xl-start {

&#x20;   --bs-position: início;

&#x20; }

&#x20; .dropdown-menu-xl-start\[data-bs-popper] {

&#x20;   direita: automático;

&#x20;   esquerda: 0;

&#x20; }

&#x20; .dropdown-menu-xl-end {

&#x20;   --bs-position: fim;

&#x20; }

&#x20; .dropdown-menu-xl-end\[data-bs-popper] {

&#x20;   direita: 0;

&#x20;   esquerda: automático;

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .dropdown-menu-xxl-start {

&#x20;   --bs-position: início;

&#x20; }

&#x20; .dropdown-menu-xxl-start\[data-bs-popper] {

&#x20;   direita: automático;

&#x20;   esquerda: 0;

&#x20; }

&#x20; .dropdown-menu-xxl-end {

&#x20;   --bs-position: fim;

&#x20; }

&#x20; .dropdown-menu-xxl-end\[data-bs-popper] {

&#x20;   direita: 0;

&#x20;   esquerda: automático;

&#x20; }

}

.dropup .dropdown-menu\[data-bs-popper] {

&#x20; topo: automático;

&#x20; parte inferior: 100%;

&#x20; margem superior: 0;

&#x20; margem-inferior: var(--bs-dropdown-spacer);

}

.dropup .dropdown-toggle::after {

&#x20; exibição: inline-block;

&#x20; margem esquerda: 0,255em;

&#x20; alinhamento vertical: 0,255em;

&#x20; contente: "";

&#x20; borda-superior: 0;

&#x20; borda-direita: 0,3em sólida transparente;

&#x20; borda inferior: 0,3em sólida;

&#x20; borda esquerda: 0,3em sólida transparente;

}

.dropup .dropdown-toggle:empty::after {

&#x20; margem-esquerda: 0;

}



.dropend .menu suspenso\[data-bs-popper] {

&#x20; topo: 0;

&#x20; direita: automático;

&#x20; esquerda: 100%;

&#x20; margem superior: 0;

&#x20; margem-esquerda: var(--bs-dropdown-spacer);

}

.dropend .dropdown-toggle::after {

&#x20; exibição: inline-block;

&#x20; margem esquerda: 0,255em;

&#x20; alinhamento vertical: 0,255em;

&#x20; contente: "";

&#x20; borda superior: 0,3em sólida transparente;

&#x20; borda-direita: 0;

&#x20; borda inferior: 0,3em sólida transparente;

&#x20; borda esquerda: 0,3em sólida;

}

.dropend .dropdown-toggle:empty::after {

&#x20; margem-esquerda: 0;

}

.dropend .dropdown-toggle::after {

&#x20; alinhamento vertical: 0;

}



.dropstart .dropdown-menu\[data-bs-popper] {

&#x20; topo: 0;

&#x20; direita: 100%;

&#x20; esquerda: automático;

&#x20; margem superior: 0;

&#x20; margem-direita: var(--bs-dropdown-spacer);

}

.dropstart .dropdown-toggle::depois {

&#x20; exibição: inline-block;

&#x20; margem esquerda: 0,255em;

&#x20; alinhamento vertical: 0,255em;

&#x20; contente: "";

}

.dropstart .dropdown-toggle::depois {

&#x20; exibir: nenhum;

}

.dropstart .dropdown-toggle::before {

&#x20; exibição: inline-block;

&#x20; margem-direita: 0,255em;

&#x20; alinhamento vertical: 0,255em;

&#x20; contente: "";

&#x20; borda superior: 0,3em sólida transparente;

&#x20; borda-direita: 0,3em sólida;

&#x20; borda inferior: 0,3em sólida transparente;

}

.dropstart .dropdown-toggle:empty::after {

&#x20; margem-esquerda: 0;

}

.dropstart .dropdown-toggle::before {

&#x20; alinhamento vertical: 0;

}



.dropdown-divider {

&#x20; altura: 0;

&#x20; margem: var(--bs-dropdown-divider-margin-y) 0;

&#x20; overflow: oculto;

&#x20; borda superior: 1px sólida var(--bs-dropdown-divider-bg);

&#x20; opacidade: 1;

}



.dropdown-item {

&#x20; exibir: bloco;

&#x20; largura: 100%;

&#x20; preenchimento: var(--bs-dropdown-item-padding-y) var(--bs-dropdown-item-padding-x);

&#x20; claro: ambos;

&#x20; peso da fonte: 400;

&#x20; cor: var(--bs-dropdown-link-color);

&#x20; alinhamento de texto: herdar;

&#x20; decoração de texto: nenhuma;

&#x20; espaço em branco: nowrap;

&#x20; cor de fundo: transparente;

&#x20; borda: 0;

&#x20; raio-da-borda: var(--bs-dropdown-item-border-radius, 0);

}

.dropdown-item:hover, .dropdown-item:focus {

&#x20; cor: var(--bs-dropdown-link-hover-color);

&#x20; cor de fundo: var(--bs-dropdown-link-hover-bg);

}

.dropdown-item.active, .dropdown-item:active {

&#x20; cor: var(--bs-dropdown-link-active-color);

&#x20; decoração de texto: nenhuma;

&#x20; cor de fundo: var(--bs-dropdown-link-active-bg);

}

.dropdown-item.disabled, .dropdown-item:disabled {

&#x20; cor: var(--bs-dropdown-link-disabled-color);

&#x20; eventos-ponteiro: nenhum;

&#x20; cor de fundo: transparente;

}



.dropdown-menu.show {

&#x20; exibir: bloco;

}



.dropdown-header {

&#x20; exibir: bloco;

&#x20; preenchimento: var(--bs-dropdown-header-padding-y) var(--bs-dropdown-header-padding-x);

&#x20; margem-inferior: 0;

&#x20; tamanho da fonte: 0,875rem;

&#x20; cor: var(--bs-dropdown-header-color);

&#x20; espaço em branco: nowrap;

}



.dropdown-item-text {

&#x20; exibir: bloco;

&#x20; preenchimento: var(--bs-dropdown-item-padding-y) var(--bs-dropdown-item-padding-x);

&#x20; cor: var(--bs-dropdown-link-color);

}



.dropdown-menu-dark {

&#x20; --bs-dropdown-color: #dee2e6;

&#x20; --bs-dropdown-bg: #343a40;

&#x20; --bs-dropdown-border-color: var(--bs-border-color-translucent);

&#x20; --bs-dropdown-box-shadow: ;

&#x20; --bs-dropdown-link-color: #dee2e6;

&#x20; --bs-dropdown-link-hover-color: #fff;

&#x20; --bs-dropdown-divider-bg: var(--bs-border-color-translucent);

&#x20; --bs-dropdown-link-hover-bg: rgba(255, 255, 255, 0.15);

&#x20; --bs-dropdown-link-active-color: #fff;

&#x20; --bs-dropdown-link-active-bg: #0d6efd;

&#x20; --bs-dropdown-link-disabled-color: #adb5bd;

&#x20; --bs-dropdown-header-color: #adb5bd;

}



.btn-group,

.btn-group-vertical {

&#x20; posição: relativa;

&#x20; exibição: inline-flex;

&#x20; alinhamento vertical: meio;

}

.btn-group > .btn,

.btn-group-vertical > .btn {

&#x20; posição: relativa;

&#x20; flex: 1 1 auto;

}

.btn-group > .btn-check:checked + .btn,

.btn-group > .btn-check:focus + .btn,

.btn-group > .btn:hover,

.btn-group > .btn:focus,

.btn-group > .btn:ativo,

.btn-group > .btn.active,

.btn-group-vertical > .btn-check:checked + .btn,

.btn-group-vertical > .btn-check:focus + .btn,

.btn-group-vertical > .btn:hover,

.btn-group-vertical > .btn:focus,

.btn-group-vertical > .btn:ativo,

.btn-group-vertical > .btn.active {

&#x20; Índice z: 1;

}



.btn-toolbar {

&#x20; Exibir: flexível;

&#x20; flex-wrap: envolver;

&#x20; justify-content: flex-start;

}

.btn-toolbar .input-group {

&#x20; largura: automática;

}



.btn-group {

&#x20; raio da borda: var(--bs-raio da borda);

}

.btn-group > :not(.btn-check:first-child) + .btn,

.btn-group > .btn-group:not(:first-child) {

&#x20; margem-esquerda: calc(var(--bs-border-width) \* -1);

}

.btn-group > .btn:not(:last-child):not(.dropdown-toggle),

.btn-group > .btn.dropdown-toggle-split:first-child,

.btn-group > .btn-group:not(:last-child) > .btn {

&#x20; raio-superior-direito-da-borda: 0;

&#x20; raio-inferior-direito-da-borda: 0;

}

.btn-group > .btn:nth-child(n+3),

.btn-group > :not(.btn-check) + .btn,

.btn-group > .btn-group:not(:first-child) > .btn {

&#x20; raio-superior-esquerdo-da-borda: 0;

&#x20; raio-da-borda-inferior-esquerda: 0;

}



.dropdown-toggle-split {

&#x20; preenchimento à direita: 0,5625rem;

&#x20; preenchimento à esquerda: 0,5625rem;

}

.dropdown-toggle-split::after, .dropup .dropdown-toggle-split::after, .dropend .dropdown-toggle-split::after {

&#x20; margem-esquerda: 0;

}

.dropstart .dropdown-toggle-split::before {

&#x20; margem-direita: 0;

}



.btn-sm + .dropdown-toggle-split, .btn-group-sm > .btn + .dropdown-toggle-split {

&#x20; preenchimento à direita: 0,375rem;

&#x20; preenchimento à esquerda: 0,375rem;

}



.btn-lg + .dropdown-toggle-split, .btn-group-lg > .btn + .dropdown-toggle-split {

&#x20; preenchimento à direita: 0,75rem;

&#x20; preenchimento à esquerda: 0,75rem;

}



.btn-group-vertical {

&#x20; flex-direction: coluna;

&#x20; alinhamento-itens: início-flexível;

&#x20; justificar-conteúdo: centralizado;

}

.btn-group-vertical > .btn,

.btn-group-vertical > .btn-group {

&#x20; largura: 100%;

}

.btn-group-vertical > .btn:not(:first-child),

.btn-group-vertical > .btn-group:not(:first-child) {

&#x20; margem-superior: calc(var(--bs-border-width) \* -1);

}

.btn-group-vertical > .btn:not(:last-child):not(.dropdown-toggle),

.btn-group-vertical > .btn-group:not(:last-child) > .btn {

&#x20; raio-inferior-direito-da-borda: 0;

&#x20; raio-da-borda-inferior-esquerda: 0;

}

.btn-group-vertical > .btn \~ .btn,

.btn-group-vertical > .btn-group:not(:first-child) > .btn {

&#x20; raio-superior-esquerdo-da-borda: 0;

&#x20; raio-superior-direito-da-borda: 0;

}



.nav {

&#x20; --bs-nav-link-padding-x: 1rem;

&#x20; --bs-nav-link-padding-y: 0.5rem;

&#x20; --bs-nav-link-font-weight: ;

&#x20; --bs-nav-link-color: var(--bs-link-color);

&#x20; --bs-link-hover-color: var(--bs-link-hover-color);

&#x20; --bs-nav-link-disabled-color: var(--bs-secondary-color);

&#x20; Exibir: flexível;

&#x20; flex-wrap: envolver;

&#x20; preenchimento-esquerdo: 0;

&#x20; margem-inferior: 0;

&#x20; estilo de lista: nenhum;

}



.nav-link {

&#x20; exibir: bloco;

&#x20; preenchimento: var(--bs-nav-link-padding-y) var(--bs-nav-link-padding-x);

&#x20; tamanho-da-fonte: var(--bs-nav-link-font-size);

&#x20; peso-da-fonte: var(--bs-nav-link-font-weight);

&#x20; cor: var(--bs-nav-link-color);

&#x20; decoração de texto: nenhuma;

&#x20; Contexto: nenhum;

&#x20; borda: 0;

&#x20; transição: cor 0,15s ease-in-out, cor de fundo 0,15s ease-in-out, cor da borda 0,15s ease-in-out;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .nav-link {

&#x20;   transição: nenhuma;

&#x20; }

}

.nav-link:hover, .nav-link:focus {

&#x20; cor: var(--bs-nav-link-hover-color);

}

.nav-link:focus-visible {

&#x20; esboço: 0;

&#x20; box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

}

.nav-link.disabled {

&#x20; cor: var(--bs-nav-link-disabled-color);

&#x20; eventos-ponteiro: nenhum;

&#x20; cursor: padrão;

}



.nav-tabs {

&#x20; --bs-nav-tabs-border-width: var(-bs-border-width);

&#x20; --bs-nav-tabs-border-color: var(--bs-border-color);

&#x20; --bs-nav-tabs-border-radius: var(--bs-border-radius);

&#x20; --bs-nav-tabs-link-hover-border-color: var(--bs-secondary-bg) var(--bs-secondary-bg) var(--bs-border-color);

&#x20; --bs-nav-tabs-link-active-color: var(--bs-emphasis-color);

&#x20; --bs-nav-tabs-link-active-bg: var(--bs-body-bg);

&#x20; --bs-nav-tabs-link-active-border-color: var(--bs-border-color) var(--bs-border-color) var(--bs-body-bg);

&#x20; borda inferior: var(--bs-nav-tabs-border-width) sólido var(--bs-nav-tabs-border-color);

}

.nav-tabs .nav-link {

&#x20; margem-inferior: calc(-1 \* var(--bs-nav-tabs-border-width));

&#x20; borda: var(--bs-nav-tabs-border-width) sólido transparente;

&#x20; border-top-left-radius: var(--bs-nav-tabs-border-radius);

&#x20; raio superior direito da borda: var(-bs-nav-tabs-raio da borda);

}

.nav-tabs .nav-link:hover, .nav-tabs .nav-link:focus {

&#x20; isolamento: isolar;

&#x20; cor-da-borda: var(--bs-nav-tabs-link-hover-border-color);

}

.nav-tabs .nav-link.disabled, .nav-tabs .nav-link:disabled {

&#x20; cor: var(--bs-nav-link-disabled-color);

&#x20; cor de fundo: transparente;

&#x20; cor da borda: transparente;

}

.nav-tabs .nav-link.active,

.nav-tabs .nav-item.show .nav-link {

&#x20; cor: var(--bs-nav-tabs-link-active-color);

&#x20; cor de fundo: var(--bs-nav-tabs-link-active-bg);

&#x20; cor-da-borda: var(--bs-nav-tabs-link-active-border-color);

}

.nav-tabs .dropdown-menu {

&#x20; margem superior: calc(-1 \* var(--bs-nav-tabs-border-width));

&#x20; raio-superior-esquerdo-da-borda: 0;

&#x20; raio-superior-direito-da-borda: 0;

}



.nav-pills {

&#x20; --bs-nav-pills-border-radius: var(--bs-border-radius);

&#x20; --bs-nav-pills-link-active-color: #fff;

&#x20; --bs-nav-pills-link-active-bg: #0d6efd;

}

.nav-pills .nav-link {

&#x20; raio da fronteira: var(--bs-nav-pills-border-radius);

}

.nav-pills .nav-link:desativado {

&#x20; cor: var(--bs-nav-link-disabled-color);

&#x20; cor de fundo: transparente;

&#x20; cor da borda: transparente;

}

.nav-pills .nav-link.active,

.nav-pills .show > .nav-link {

&#x20; cor: var(--bs-nav-pills-link-active-color);

&#x20; cor de fundo: var(--bs-nav-pills-link-active-bg);

}



.nav-underline {

&#x20; --bs-nav-underline-gap: 1rem;

&#x20; --bs-nav-underline-border-width: 0.125rem;

&#x20; --bs-nav-underline-link-active-color: var(--bs-emphasis-color);

&#x20; lacuna: var(--bs-nav-underline-gap);

}

.nav-underline .nav-link {

&#x20; preenchimento à direita: 0;

&#x20; preenchimento-esquerdo: 0;

&#x20; borda-inferior: var(--bs-nav-underline-border-width) sólida transparente;

}

.nav-underline .nav-link:hover, .nav-underline .nav-link:focus {

&#x20; cor-da-borda-inferior: cor-atual;

}

.nav-underline .nav-link.active,

.nav-underline .show > .nav-link {

&#x20; peso da fonte: 700;

&#x20; cor: var(--bs-nav-underline-link-active-color);

&#x20; cor-da-borda-inferior: cor-atual;

}



.nav-fill > .nav-link,

.nav-fill .nav-item {

&#x20; flex: 1 1 auto;

&#x20; alinhamento do texto: centralizado;

}



.nav-justificado > .nav-link,

.nav-justified .nav-item {

&#x20; base flexível: 0;

&#x20; flex-grow: 1;

&#x20; alinhamento do texto: centralizado;

}



.nav-fill .nav-item .nav-link,

.nav-justified .nav-item .nav-link {

&#x20; largura: 100%;

}



.tab-content > .tab-pane {

&#x20; exibir: nenhum;

}

.tab-content > .active {

&#x20; exibir: bloco;

}



.navbar {

&#x20; --bs-navbar-padding-x: 0;

&#x20; --bs-navbar-padding-y: 0,5rem;

&#x20; --bs-navbar-color: rgba(var(--bs-emphasis-color-rgb), 0.65);

&#x20; --bs-navbar-hover-color: rgba(var(--bs-emphasis-color-rgb), 0.8);

&#x20; --bs-navbar-disabled-color: rgba(var(--bs-emphasis-color-rgb), 0.3);

&#x20; --bs-navbar-active-color: rgba(var(--bs-emphasis-color-rgb), 1);

&#x20; --bs-navbar-brand-padding-y: 0.3125rem;

&#x20; --bs-navbar-marca-margem-fim: 1rem;

&#x20; --bs-navbar-brand-font-size: 1.25rem;

&#x20; --bs-navbar-brand-color: rgba(var(--bs-emphasis-color-rgb), 1);

&#x20; --bs-navbar-brand-hover-color: rgba(var(--bs-emphasis-color-rgb), 1);

&#x20; --bs-navbar-nav-link-padding-x: 0.5rem;

&#x20; --bs-navbar-toggler-padding-y: 0,25rem;

&#x20; --bs-navbar-toggler-padding-x: 0.75rem;

&#x20; --bs-navbar-toggler-font-size: 1.25rem;

&#x20; --bs-navbar-toggler-icon-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba%2833, 37, 41, 0.75%29' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");

&#x20; --bs-navbar-toggler-border-color: rgba(var(--bs-emphasis-color-rgb), 0.15);

&#x20; --bs-navbar-toggler-border-radius: var(--bs-border-radius);

&#x20; --bs-navbar-toggler-focus-width: 0.25rem;

&#x20; --bs-navbar-toggler-transition: box-shadow 0.15s ease-in-out;

&#x20; posição: relativa;

&#x20; Exibir: flexível;

&#x20; flex-wrap: envolver;

&#x20; alinhamento-itens: centro;

&#x20; justify-content: espaço-entre;

&#x20; preenchimento: var(--bs-navbar-padding-y) var(--bs-navbar-padding-x);

}

.navbar > .container,

.navbar > .container-fluid,

.navbar > .container-sm,

.navbar > .container-md,

.navbar > .container-lg,

.navbar > .container-xl,

.navbar > .container-xxl {

&#x20; Exibir: flexível;

&#x20; flex-wrap: herdar;

&#x20; alinhamento-itens: centro;

&#x20; justify-content: espaço-entre;

}

.navbar-brand {

&#x20; padding-top: var(--bs-navbar-brand-padding-y);

&#x20; preenchimento inferior: var(--bs-navbar-brand-padding-y);

&#x20; margem direita: var(--bs-navbar-brand-margin-end);

&#x20; tamanho-da-fonte: var(--bs-navbar-brand-font-size);

&#x20; cor: var(--bs-navbar-brand-color);

&#x20; decoração de texto: nenhuma;

&#x20; espaço em branco: nowrap;

}

.navbar-brand:hover, .navbar-brand:focus {

&#x20; cor: var(--bs-navbar-brand-hover-color);

}



.navbar-nav {

&#x20; --bs-nav-link-padding-x: 0;

&#x20; --bs-nav-link-padding-y: 0.5rem;

&#x20; --bs-nav-link-font-weight: ;

&#x20; --bs-nav-link-color: var(--bs-navbar-color);

&#x20; --bs-nav-link-hover-color: var(--bs-navbar-hover-color);

&#x20; --bs-nav-link-disabled-color: var(--bs-navbar-disabled-color);

&#x20; Exibir: flexível;

&#x20; flex-direction: coluna;

&#x20; preenchimento-esquerdo: 0;

&#x20; margem-inferior: 0;

&#x20; estilo de lista: nenhum;

}

.navbar-nav .nav-link.active, .navbar-nav .nav-link.show {

&#x20; cor: var(--bs-navbar-active-color);

}

.navbar-nav .dropdown-menu {

&#x20; posição: estática;

}



.navbar-texto {

&#x20; padding-top: 0.5rem;

&#x20; padding-bottom: 0.5rem;

&#x20; cor: var(--bs-navbar-color);

}

.navbar-texto a,

.navbar-text a:hover,

.navbar-text a:focus {

&#x20; cor: var(--bs-navbar-active-color);

}



.navbar-collapse {

&#x20; Base flexível: 100%;

&#x20; flex-grow: 1;

&#x20; alinhamento-itens: centro;

}



.navbar-toggler {

&#x20; preenchimento: var(--bs-navbar-toggler-padding-y) var(--bs-navbar-toggler-padding-x);

&#x20; tamanho da fonte: var(--bs-navbar-toggler-font-size);

&#x20; altura da linha: 1;

&#x20; cor: var(--bs-navbar-color);

&#x20; cor de fundo: transparente;

&#x20; borda: var(--bs-border-width) var sólido(--bs-navbar-toggler-border-color);

&#x20; raio da borda: var(--bs-navbar-toggler-border-radius);

&#x20; transição: var(--bs-navbar-toggler-transition);

}

@media (prefers-reduced-motion: reduce) {

&#x20; .navbar-toggler {

&#x20;   transição: nenhuma;

&#x20; }

}

.navbar-toggler:hover {

&#x20; decoração de texto: nenhuma;

}

.navbar-toggler:focus {

&#x20; decoração de texto: nenhuma;

&#x20; esboço: 0;

&#x20; box-shadow: 0 0 0 var(--bs-navbar-toggler-focus-width);

}



.navbar-toggler-icon {

&#x20; exibição: inline-block;

&#x20; largura: 1,5em;

&#x20; altura: 1,5em;

&#x20; alinhamento vertical: meio;

&#x20; imagem de fundo: var(--bs-navbar-toggler-icon-bg);

&#x20; background-repeat: no-repeat;

&#x20; posição de fundo: centro;

&#x20; tamanho de fundo: 100%;

}



.navbar-nav-scroll {

&#x20; altura-máxima: var(--bs-scroll-height, 75vh);

&#x20; overflow-y: automático;

}



@media (min-width: 576px) {

&#x20; .navbar-expand-sm {

&#x20;   flex-wrap: nowrap;

&#x20;   justify-content: flex-start;

&#x20; }

&#x20; .navbar-expand-sm .navbar-nav {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .navbar-expand-sm .navbar-nav .dropdown-menu {

&#x20;   posição: absoluta;

&#x20; }

&#x20; .navbar-expand-sm .navbar-nav .nav-link {

&#x20;   padding-right: var(--bs-navbar-nav-link-padding-x);

&#x20;   padding-left: var(--bs-navbar-nav-link-padding-x);

&#x20; }

&#x20; .navbar-expand-sm .navbar-nav-scroll {

&#x20;   transbordamento: visível;

&#x20; }

&#x20; .navbar-expand-sm .navbar-collapse {

&#x20;   exibir: flex !importante;

&#x20;   flex-base: automático;

&#x20; }

&#x20; .navbar-expand-sm .navbar-toggler {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-sm .offcanvas {

&#x20;   posição: estática;

&#x20;   z-index: automático;

&#x20;   flex-grow: 1;

&#x20;   largura: automática !importante;

&#x20;   altura: automática !importante;

&#x20;   visibilidade: visível !importante;

&#x20;   cor de fundo: transparente !importante;

&#x20;   borda: 0 !importante;

&#x20;   transformar: nenhuma !importante;

&#x20;   transição: nenhuma;

&#x20; }

&#x20; .navbar-expand-sm .offcanvas .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-sm .offcanvas .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20; }

}

@media (min-width: 768px) {

&#x20; .navbar-expand-md {

&#x20;   flex-wrap: nowrap;

&#x20;   justify-content: flex-start;

&#x20; }

&#x20; .navbar-expand-md .navbar-nav {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .navbar-expand-md .navbar-nav .dropdown-menu {

&#x20;   posição: absoluta;

&#x20; }

&#x20; .navbar-expand-md .navbar-nav .nav-link {

&#x20;   padding-right: var(--bs-navbar-nav-link-padding-x);

&#x20;   padding-left: var(--bs-navbar-nav-link-padding-x);

&#x20; }

&#x20; .navbar-expand-md .navbar-nav-scroll {

&#x20;   transbordamento: visível;

&#x20; }

&#x20; .navbar-expand-md .navbar-collapse {

&#x20;   exibir: flex !importante;

&#x20;   flex-base: automático;

&#x20; }

&#x20; .navbar-expand-md .navbar-toggler {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-md .offcanvas {

&#x20;   posição: estática;

&#x20;   z-index: automático;

&#x20;   flex-grow: 1;

&#x20;   largura: automática !importante;

&#x20;   altura: automática !importante;

&#x20;   visibilidade: visível !importante;

&#x20;   cor de fundo: transparente !importante;

&#x20;   borda: 0 !importante;

&#x20;   transformar: nenhuma !importante;

&#x20;   transição: nenhuma;

&#x20; }

&#x20; .navbar-expand-md .offcanvas .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-md .offcanvas .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .navbar-expand-lg {

&#x20;   flex-wrap: nowrap;

&#x20;   justify-content: flex-start;

&#x20; }

&#x20; .navbar-expand-lg .navbar-nav {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .navbar-expand-lg .navbar-nav .menu suspenso {

&#x20;   posição: absoluta;

&#x20; }

&#x20; .navbar-expand-lg .navbar-nav .nav-link {

&#x20;   padding-right: var(--bs-navbar-nav-link-padding-x);

&#x20;   padding-left: var(--bs-navbar-nav-link-padding-x);

&#x20; }

&#x20; .navbar-expand-lg .navbar-nav-scroll {

&#x20;   transbordamento: visível;

&#x20; }

&#x20; .navbar-expand-lg .navbar-collapse {

&#x20;   exibir: flex !importante;

&#x20;   flex-base: automático;

&#x20; }

&#x20; .navbar-expand-lg .navbar-toggler {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-lg .offcanvas {

&#x20;   posição: estática;

&#x20;   z-index: automático;

&#x20;   flex-grow: 1;

&#x20;   largura: automática !importante;

&#x20;   altura: automática !importante;

&#x20;   visibilidade: visível !importante;

&#x20;   cor de fundo: transparente !importante;

&#x20;   borda: 0 !importante;

&#x20;   transformar: nenhuma !importante;

&#x20;   transição: nenhuma;

&#x20; }

&#x20; .navbar-expand-lg .offcanvas .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-lg .offcanvas .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .navbar-expand-xl {

&#x20;   flex-wrap: nowrap;

&#x20;   justify-content: flex-start;

&#x20; }

&#x20; .navbar-expand-xl .navbar-nav {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .navbar-expand-xl .navbar-nav .dropdown-menu {

&#x20;   posição: absoluta;

&#x20; }

&#x20; .navbar-expand-xl .navbar-nav .nav-link {

&#x20;   padding-right: var(--bs-navbar-nav-link-padding-x);

&#x20;   padding-left: var(--bs-navbar-nav-link-padding-x);

&#x20; }

&#x20; .navbar-expand-xl .navbar-nav-scroll {

&#x20;   transbordamento: visível;

&#x20; }

&#x20; .navbar-expand-xl .navbar-collapse {

&#x20;   exibir: flex !importante;

&#x20;   flex-base: automático;

&#x20; }

&#x20; .navbar-expand-xl .navbar-toggler {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-xl .offcanvas {

&#x20;   posição: estática;

&#x20;   z-index: automático;

&#x20;   flex-grow: 1;

&#x20;   largura: automática !importante;

&#x20;   altura: automática !importante;

&#x20;   visibilidade: visível !importante;

&#x20;   cor de fundo: transparente !importante;

&#x20;   borda: 0 !importante;

&#x20;   transformar: nenhuma !importante;

&#x20;   transição: nenhuma;

&#x20; }

&#x20; .navbar-expand-xl .offcanvas .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-xl .offcanvas .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .navbar-expand-xxl {

&#x20;   flex-wrap: nowrap;

&#x20;   justify-content: flex-start;

&#x20; }

&#x20; .navbar-expand-xxl .navbar-nav {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .navbar-expand-xxl .navbar-nav .dropdown-menu {

&#x20;   posição: absoluta;

&#x20; }

&#x20; .navbar-expand-xxl .navbar-nav .nav-link {

&#x20;   padding-right: var(--bs-navbar-nav-link-padding-x);

&#x20;   padding-left: var(--bs-navbar-nav-link-padding-x);

&#x20; }

&#x20; .navbar-expand-xxl .navbar-nav-scroll {

&#x20;   transbordamento: visível;

&#x20; }

&#x20; .navbar-expand-xxl .navbar-collapse {

&#x20;   exibir: flex !importante;

&#x20;   flex-base: automático;

&#x20; }

&#x20; .navbar-expand-xxl .navbar-toggler {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-xxl .offcanvas {

&#x20;   posição: estática;

&#x20;   z-index: automático;

&#x20;   flex-grow: 1;

&#x20;   largura: automática !importante;

&#x20;   altura: automática !importante;

&#x20;   visibilidade: visível !importante;

&#x20;   cor de fundo: transparente !importante;

&#x20;   borda: 0 !importante;

&#x20;   transformar: nenhuma !importante;

&#x20;   transição: nenhuma;

&#x20; }

&#x20; .navbar-expand-xxl .offcanvas .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .navbar-expand-xxl .offcanvas .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20; }

}

.navbar-expand {

&#x20; flex-wrap: nowrap;

&#x20; justify-content: flex-start;

}

.navbar-expand .navbar-nav {

&#x20; flex-direction: linha;

}

.navbar-expandir .navbar-nav .menu suspenso {

&#x20; posição: absoluta;

}

.navbar-expandir .navbar-nav .nav-link {

&#x20; padding-right: var(--bs-navbar-nav-link-padding-x);

&#x20; padding-left: var(--bs-navbar-nav-link-padding-x);

}

.navbar-expandir .navbar-nav-scroll {

&#x20; transbordamento: visível;

}

.navbar-expandir .navbar-collapse {

&#x20; exibir: flex !importante;

&#x20; flex-base: automático;

}

.navbar-expandir .navbar-toggler {

&#x20; exibir: nenhum;

}

.navbar-expand .offcanvas {

&#x20; posição: estática;

&#x20; z-index: automático;

&#x20; flex-grow: 1;

&#x20; largura: automática !importante;

&#x20; altura: automática !importante;

&#x20; visibilidade: visível !importante;

&#x20; cor de fundo: transparente !importante;

&#x20; borda: 0 !importante;

&#x20; transformar: nenhuma !importante;

&#x20; transição: nenhuma;

}

.navbar-expand .offcanvas .offcanvas-header {

&#x20; exibir: nenhum;

}

.navbar-expand .offcanvas .offcanvas-body {

&#x20; Exibir: flexível;

&#x20; flex-grow: 0;

&#x20; preenchimento: 0;

&#x20; overflow-y: visível;

}



.navbar-dark,

.navbar\[data-bs-theme=dark] {

&#x20; --bs-navbar-color: rgba(255, 255, 255, 0.55);

&#x20; --bs-navbar-hover-color: rgba(255, 255, 255, 0.75);

&#x20; --bs-navbar-disabled-color: rgba(255, 255, 255, 0.25);

&#x20; --bs-navbar-active-color: #fff;

&#x20; --bs-navbar-brand-color: #fff;

&#x20; --bs-navbar-brand-hover-color: #fff;

&#x20; --bs-navbar-toggler-border-color: rgba(255, 255, 255, 0.1);

&#x20; --bs-navbar-toggler-icon-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba%28255, 255, 255, 0.55%29' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");

}



\[data-bs-theme=dark] .navbar-toggler-icon {

&#x20; --bs-navbar-toggler-icon-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba%28255, 255, 255, 0.55%29' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");

}



.card {

&#x20; --bs-card-spacer-y: 1rem;

&#x20; --bs-card-spacer-x: 1rem;

&#x20; --bs-card-title-spacer-y: 0.5rem;

&#x20; --bs-card-title-color: ;

&#x20; --bs-card-subtitle-color: ;

&#x20; --bs-card-border-width: var(--bs-border-width);

&#x20; --bs-card-border-color: var(--bs-border-color-translucent);

&#x20; --bs-card-border-radius: var(--bs-border-radius);

&#x20; --bs-card-box-shadow: ;

&#x20; --bs-card-inner-border-radius: calc(var(--bs-border-radius) - (var(--bs-border-width)));

&#x20; --bs-card-cap-padding-y: 0.5rem;

&#x20; --bs-card-cap-padding-x: 1rem;

&#x20; --bs-card-cap-bg: rgba(var(--bs-body-color-rgb), 0.03);

&#x20; --bs-card-cap-color: ;

&#x20; --bs-card-height: ;

&#x20; --bs-card-color: ;

&#x20; --bs-card-bg: var(--bs-body-bg);

&#x20; --bs-card-img-overlay-padding: 1rem;

&#x20; --bs-card-group-margin: 0.75rem;

&#x20; posição: relativa;

&#x20; Exibir: flexível;

&#x20; flex-direction: coluna;

&#x20; largura mínima: 0;

&#x20; altura: var(--bs-card-height);

&#x20; cor: var(--bs-body-color);

&#x20; quebra-de-palavra: quebra-de-palavra;

&#x20; cor de fundo: var(--bs-card-bg);

&#x20; recorte de fundo: caixa de borda;

&#x20; borda: var(--bs-card-border-width) sólida var(--bs-card-border-color);

&#x20; raio-da-borda: var(--bs-card-border-radius);

}

.card > hr {

&#x20; margem-direita: 0;

&#x20; margem-esquerda: 0;

}

.card > .list-group {

&#x20; borda-superior: herdar;

&#x20; borda-inferior: herdar;

}

.card > .list-group:first-child {

&#x20; largura-superior-da-borda: 0;

&#x20; raio-borda-superior-esquerda: var(--bs-card-inner-border-radius);

&#x20; raio-topo-direito-da-borda: var(--bs-card-inner-border-radius);

}

.card > .list-group:last-child {

&#x20; largura-inferior-da-borda: 0;

&#x20; raio-borda-inferior-direita: var(--bs-card-inner-border-radius);

&#x20; raio-borda-inferior-esquerda: var(--bs-card-inner-border-radius);

}

.card > .card-header + .list-group,

.card > .list-group + .card-footer {

&#x20; borda-superior: 0;

}



.card-body {

&#x20; flex: 1 1 auto;

&#x20; preenchimento: var(--bs-card-spacer-y) var(--bs-card-spacer-x);

&#x20; cor: var(--bs-card-color);

}



.card-title {

&#x20; margem-inferior: var(--bs-card-title-spacer-y);

&#x20; cor: var(--bs-card-title-color);

}



.card-subtitle {

&#x20; margem-superior: calc(-0.5 \* var(--bs-card-title-spacer-y));

&#x20; margem-inferior: 0;

&#x20; cor: var(--bs-card-subtitle-color);

}



.card-text:last-child {

&#x20; margem-inferior: 0;

}



.card-link + .card-link {

&#x20; margem-esquerda: var(--bs-card-spacer-x);

}



.card-header {

&#x20; preenchimento: var(--bs-card-cap-padding-y) var(--bs-card-cap-padding-x);

&#x20; margem-inferior: 0;

&#x20; cor: var(--bs-card-cap-color);

&#x20; cor de fundo: var(--bs-card-cap-bg);

&#x20; borda-inferior: var(--bs-card-border-width) sólida var(--bs-card-border-color);

}

.card-header:first-child {

&#x20; raio-da-borda: var(--bs-card-inner-border-radius) var(--bs-card-inner-border-radius) 0 0;

}



.card-footer {

&#x20; preenchimento: var(--bs-card-cap-padding-y) var(--bs-card-cap-padding-x);

&#x20; cor: var(--bs-card-cap-color);

&#x20; cor de fundo: var(--bs-card-cap-bg);

&#x20; borda-superior: var(--bs-card-border-width) sólida var(--bs-card-border-color);

}

.card-footer:last-child {

&#x20; border-radius: 0 0 var(--bs-card-inner-border-radius) var(--bs-card-inner-border-radius);

}



.card-header-tabs {

&#x20; margem-direita: calc(-0.5 \* var(--bs-card-cap-padding-x));

&#x20; margem-inferior: calc(-1 \* var(--bs-card-cap-padding-y));

&#x20; margem-esquerda: calc(-0.5 \* var(--bs-card-cap-padding-x));

&#x20; borda-inferior: 0;

}

.card-header-tabs .nav-link.active {

&#x20; cor de fundo: var(--bs-card-bg);

&#x20; cor-borda-inferior: var(--bs-card-bg);

}



.card-header-pills {

&#x20; margem-direita: calc(-0.5 \* var(--bs-card-cap-padding-x));

&#x20; margem-esquerda: calc(-0.5 \* var(--bs-card-cap-padding-x));

}



.card-img-overlay {

&#x20; posição: absoluta;

&#x20; topo: 0;

&#x20; direita: 0;

&#x20; parte inferior: 0;

&#x20; esquerda: 0;

&#x20; preenchimento: var(--bs-card-img-overlay-padding);

&#x20; raio-da-borda: var(--bs-card-inner-border-radius);

}



.card-img,

.card-img-top,

.card-img-bottom {

&#x20; largura: 100%;

}



.card-img,

.card-img-top {

&#x20; raio-borda-superior-esquerda: var(--bs-card-inner-border-radius);

&#x20; raio-topo-direito-da-borda: var(--bs-card-inner-border-radius);

}



.card-img,

.card-img-bottom {

&#x20; raio-borda-inferior-direita: var(--bs-card-inner-border-radius);

&#x20; raio-borda-inferior-esquerda: var(--bs-card-inner-border-radius);

}



.card-group > .card {

&#x20; margem-inferior: var(--bs-card-group-margin);

}

@media (min-width: 576px) {

&#x20; .card-group {

&#x20;   Exibir: flexível;

&#x20;   flex-flow: quebra de linha;

&#x20; }

&#x20; .card-group > .card {

&#x20;   flex: 1 0 0%;

&#x20;   margem-inferior: 0;

&#x20; }

&#x20; .card-group > .card + .card {

&#x20;   margem-esquerda: 0;

&#x20;   borda-esquerda: 0;

&#x20; }

&#x20; .card-group > .card:not(:last-child) {

&#x20;   raio-superior-direito-da-borda: 0;

&#x20;   raio-inferior-direito-da-borda: 0;

&#x20; }

&#x20; .card-group > .card:not(:last-child) .card-img-top,

&#x20; .card-group > .card:not(:last-child) .card-header {

&#x20;   raio-superior-direito-da-borda: 0;

&#x20; }

&#x20; .card-group > .card:not(:last-child) .card-img-bottom,

&#x20; .card-group > .card:not(:last-child) .card-footer {

&#x20;   raio-inferior-direito-da-borda: 0;

&#x20; }

&#x20; .card-group > .card:not(:first-child) {

&#x20;   raio-superior-esquerdo-da-borda: 0;

&#x20;   raio-da-borda-inferior-esquerda: 0;

&#x20; }

&#x20; .card-group > .card:not(:first-child) .card-img-top,

&#x20; .card-group > .card:not(:first-child) .card-header {

&#x20;   raio-superior-esquerdo-da-borda: 0;

&#x20; }

&#x20; .card-group > .card:not(:first-child) .card-img-bottom,

&#x20; .card-group > .card:not(:first-child) .card-footer {

&#x20;   raio-da-borda-inferior-esquerda: 0;

&#x20; }

}



.acordeão {

&#x20; --bs-accordion-color: var(--bs-body-color);

&#x20; --bs-acordeão-bg: var(--bs-body-bg);

&#x20; --bs-accordion-transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out, border-radius 0.15s ease;

&#x20; --bs-accordion-border-color: var(--bs-border-color);

&#x20; --bs-accordion-border-width: var(--bs-border-width);

&#x20; --bs-acordeão-raio da borda: var(--bs-raio da borda);

&#x20; --bs-accordion-inner-border-radius: calc(var(--bs-border-radius) - (var(--bs-border-width)));

&#x20; --bs-accordion-btn-padding-x: 1.25rem;

&#x20; --bs-accordion-btn-padding-y: 1rem;

&#x20; --bs-accordion-btn-color: var(--bs-body-color);

&#x20; --bs-acordeão-btn-bg: var(--bs-acordeão-bg);

&#x20; --bs-accordion-btn-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23212529'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");

&#x20; --bs-accordion-btn-icon-width: 1.25rem;

&#x20; --bs-accordion-btn-icon-transform: rotate(-180deg);

&#x20; --bs-accordion-btn-icon-transition: transform 0.2s ease-in-out;

&#x20; --bs-accordion-btn-active-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23052c65'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");

&#x20; --bs-accordion-btn-focus-border-color: #86b7fe;

&#x20; --bs-accordion-btn-focus-box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

&#x20; --bs-accordion-body-padding-x: 1.25rem;

&#x20; --bs-accordion-body-padding-y: 1rem;

&#x20; --bs-accordion-active-color: var(--bs-primary-text-emphasis);

&#x20; --bs-accordion-active-bg: var(--bs-primary-bg-subtle);

}



.accordion-button {

&#x20; posição: relativa;

&#x20; Exibir: flexível;

&#x20; alinhamento-itens: centro;

&#x20; largura: 100%;

&#x20; preenchimento: var(--bs-accordion-btn-padding-y) var(--bs-accordion-btn-padding-x);

&#x20; tamanho da fonte: 1rem;

&#x20; cor: var(--bs-accordion-btn-color);

&#x20; alinhamento de texto: esquerda;

&#x20; cor de fundo: var(--bs-accordion-btn-bg);

&#x20; borda: 0;

&#x20; raio-da-borda: 0;

&#x20; âncora de transbordamento: nenhuma;

&#x20; transição: var(--bs-accordion-transition);

}

@media (prefers-reduced-motion: reduce) {

&#x20; .accordion-button {

&#x20;   transição: nenhuma;

&#x20; }

}

.accordion-button:not(.collapsed) {

&#x20; cor: var(--bs-accordion-active-color);

&#x20; cor de fundo: var(--bs-accordion-active-bg);

&#x20; box-shadow: inset 0 calc(-1 \* var(--bs-accordion-border-width)) 0 var(--bs-accordion-border-color);

}

.accordion-button:not(.collapsed)::after {

&#x20; background-image: var(--bs-accordion-btn-active-icon);

&#x20; transformar: var(--bs-accordion-btn-icon-transform);

}

.accordion-button::after {

&#x20; flex-shrink: 0;

&#x20; largura: var(--bs-accordion-btn-icon-width);

&#x20; altura: var(--bs-accordion-btn-icon-width);

&#x20; margem-esquerda: automática;

&#x20; contente: "";

&#x20; background-image: var(--bs-accordion-btn-icon);

&#x20; background-repeat: no-repeat;

&#x20; tamanho de fundo: var(--bs-accordion-btn-icon-width);

&#x20; transição: var(--bs-accordion-btn-icon-transition);

}

@media (prefers-reduced-motion: reduce) {

&#x20; .accordion-button::after {

&#x20;   transição: nenhuma;

&#x20; }

}

.accordion-button:hover {

&#x20; Índice z: 2;

}

.accordion-button:focus {

&#x20; Índice z: 3;

&#x20; cor-da-borda: var(--bs-accordion-btn-focus-border-color);

&#x20; esboço: 0;

&#x20; box-shadow: var(--bs-accordion-btn-focus-box-shadow);

}



.accordion-header {

&#x20; margem-inferior: 0;

}



.accordion-item {

&#x20; cor: var(--bs-accordion-color);

&#x20; cor de fundo: var(--bs-accordion-bg);

&#x20; borda: var(--bs-accordion-border-width) solid var(--bs-accordion-border-color);

}

.accordion-item:first-of-type {

&#x20; raio-borda-superior-esquerda: var(--bs-accordion-border-radius);

&#x20; raio-topo-direito-da-borda: var(--bs-accordion-border-radius);

}

.accordion-item:first-of-type .accordion-button {

&#x20; raio-borda-superior-esquerda: var(--bs-accordion-inner-border-radius);

&#x20; raio-topo-direito-da-borda: var(--bs-accordion-inner-border-radius);

}

.accordion-item:not(:first-of-type) {

&#x20; borda-superior: 0;

}

.accordion-item:último-do-tipo {

&#x20; raio-borda-inferior-direita: var(--bs-accordion-border-radius);

&#x20; raio-da-borda-inferior-esquerda: var(--bs-accordion-border-radius);

}

.accordion-item:last-of-type .accordion-button.collapsed {

&#x20; raio-borda-inferior-direita: var(--bs-accordion-inner-border-radius);

&#x20; raio-borda-inferior-esquerda: var(--bs-accordion-inner-border-radius);

}

.accordion-item:last-of-type .accordion-collapse {

&#x20; raio-borda-inferior-direita: var(--bs-accordion-border-radius);

&#x20; raio-da-borda-inferior-esquerda: var(--bs-accordion-border-radius);

}



.accordion-body {

&#x20; preenchimento: var(--bs-accordion-body-padding-y) var(--bs-accordion-body-padding-x);

}



.accordion-flush .accordion-collapse {

&#x20; largura-da-borda: 0;

}

.accordion-flush .accordion-item {

&#x20; borda-direita: 0;

&#x20; borda-esquerda: 0;

&#x20; raio-da-borda: 0;

}

.accordion-flush .accordion-item:first-child {

&#x20; borda-superior: 0;

}

.accordion-flush .accordion-item:last-child {

&#x20; borda-inferior: 0;

}

.accordion-flush .accordion-item .accordion-button, .accordion-flush .accordion-item .accordion-button.collapsed {

&#x20; raio-da-borda: 0;

}



\[data-bs-theme=dark] .accordion-button::after {

&#x20; --bs-accordion-btn-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%236ea8fe'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");

&#x20; --bs-accordion-btn-active-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%236ea8fe'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");

}



.breadcrumb {

&#x20; --bs-breadcrumb-padding-x: 0;

&#x20; --bs-breadcrumb-padding-y: 0;

&#x20; --bs-breadcrumb-margin-bottom: 1rem;

&#x20; --bs-breadcrumb-bg: ;

&#x20; --bs-breadcrumb-border-radius: ;

&#x20; --bs-breadcrumb-divider-color: var(--bs-secondary-color);

&#x20; --bs-breadcrumb-item-padding-x: 0.5rem;

&#x20; --bs-breadcrumb-item-active-color: var(--bs-secondary-color);

&#x20; Exibir: flexível;

&#x20; flex-wrap: envolver;

&#x20; preenchimento: var(--bs-breadcrumb-padding-y) var(--bs-breadcrumb-padding-x);

&#x20; margem-inferior: var(--bs-breadcrumb-margin-bottom);

&#x20; tamanho-da-fonte: var(--bs-breadcrumb-font-size);

&#x20; estilo de lista: nenhum;

&#x20; cor de fundo: var(--bs-breadcrumb-bg);

&#x20; raio-da-borda: var(--bs-breadcrumb-border-radius);

}



.breadcrumb-item + .breadcrumb-item {

&#x20; padding-left: var(--bs-breadcrumb-item-padding-x);

}

.breadcrumb-item + .breadcrumb-item::before {

&#x20; flutuar: esquerda;

&#x20; padding-right: var(--bs-breadcrumb-item-padding-x);

&#x20; cor: var(--bs-breadcrumb-divider-color);

&#x20; conteúdo: var(--bs-breadcrumb-divider, "/") /\* rtl: var(--bs-breadcrumb-divider, "/") \*/;

}

.breadcrumb-item.active {

&#x20; cor: var(--bs-breadcrumb-item-active-color);

}



.paginação {

&#x20; --bs-pagination-padding-x: 0.75rem;

&#x20; --bs-pagination-padding-y: 0.375rem;

&#x20; --bs-pagination-font-size: 1rem;

&#x20; --bs-pagination-color: var(--bs-link-color);

&#x20; --bs-pagination-bg: var(--bs-body-bg);

&#x20; --bs-pagination-border-width: var(--bs-border-width);

&#x20; --bs-pagination-border-color: var(--bs-border-color);

&#x20; --bs-pagination-border-radius: var(--bs-border-radius);

&#x20; --bs-pagination-hover-color: var(--bs-link-hover-color);

&#x20; --bs-pagination-hover-bg: var(--bs-tertiary-bg);

&#x20; --bs-pagination-hover-border-color: var(--bs-border-color);

&#x20; --bs-pagination-focus-color: var(--bs-link-hover-color);

&#x20; --bs-pagination-focus-bg: var(--bs-secondary-bg);

&#x20; --bs-pagination-focus-box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

&#x20; --bs-pagination-active-color: #fff;

&#x20; --bs-pagination-active-bg: #0d6efd;

&#x20; --bs-pagination-active-border-color: #0d6efd;

&#x20; --bs-pagination-disabled-color: var(--bs-secondary-color);

&#x20; --bs-pagination-disabled-bg: var(--bs-secondary-bg);

&#x20; --bs-pagination-disabled-border-color: var(--bs-border-color);

&#x20; Exibir: flexível;

&#x20; preenchimento-esquerdo: 0;

&#x20; estilo de lista: nenhum;

}



.page-link {

&#x20; posição: relativa;

&#x20; exibir: bloco;

&#x20; preenchimento: var(--bs-pagination-padding-y) var(--bs-pagination-padding-x);

&#x20; tamanho-da-fonte: var(--bs-pagination-font-size);

&#x20; cor: var(--bs-pagination-color);

&#x20; decoração de texto: nenhuma;

&#x20; cor de fundo: var(--bs-pagination-bg);

&#x20; borda: var(--bs-pagination-border-width) sólida var(--bs-pagination-border-color);

&#x20; transição: cor 0,15s ease-in-out, cor de fundo 0,15s ease-in-out, cor da borda 0,15s ease-in-out, sombra da caixa 0,15s ease-in-out;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .page-link {

&#x20;   transição: nenhuma;

&#x20; }

}

.page-link:hover {

&#x20; Índice z: 2;

&#x20; cor: var(--bs-pagination-hover-color);

&#x20; cor de fundo: var(--bs-pagination-hover-bg);

&#x20; cor-da-borda: var(--bs-pagination-hover-border-color);

}

.page-link:focus {

&#x20; Índice z: 3;

&#x20; cor: var(--bs-pagination-focus-color);

&#x20; cor de fundo: var(--bs-pagination-focus-bg);

&#x20; esboço: 0;

&#x20; box-shadow: var(--bs-pagination-focus-box-shadow);

}

.page-link.active, .active > .page-link {

&#x20; Índice z: 3;

&#x20; cor: var(--bs-pagination-active-color);

&#x20; cor de fundo: var(--bs-pagination-active-bg);

&#x20; cor-da-borda: var(--bs-pagination-active-border-color);

}

.page-link.disabled, .disabled > .page-link {

&#x20; cor: var(--bs-pagination-disabled-color);

&#x20; eventos-ponteiro: nenhum;

&#x20; cor de fundo: var(--bs-pagination-disabled-bg);

&#x20; cor-da-borda: var(--bs-pagination-disabled-border-color);

}



.page-item:not(:first-child) .page-link {

&#x20; margem-esquerda: calc(var(--bs-border-width) \* -1);

}

.page-item:first-child .page-link {

&#x20; raio-borda-superior-esquerda: var(--bs-pagination-border-radius);

&#x20; raio-borda-inferior-esquerda: var(--bs-pagination-border-radius);

}

.page-item:last-child .page-link {

&#x20; raio-borda-superior-direita: var(--bs-pagination-border-radius);

&#x20; raio-borda-inferior-direita: var(--bs-pagination-border-radius);

}



.paginação-lg {

&#x20; --bs-pagination-padding-x: 1.5rem;

&#x20; --bs-pagination-padding-y: 0.75rem;

&#x20; --bs-pagination-font-size: 1.25rem;

&#x20; --bs-paginação-border-radius: var(--bs-border-radius-lg);

}



.paginação-sm {

&#x20; --bs-pagination-padding-x: 0.5rem;

&#x20; --bs-pagination-padding-y: 0.25rem;

&#x20; --bs-pagination-font-size: 0.875rem;

&#x20; --bs-pagination-border-radius: var(--bs-border-radius-sm);

}



.distintivo {

&#x20; --bs-badge-padding-x: 0.65em;

&#x20; --bs-badge-padding-y: 0.35em;

&#x20; --bs-badge-font-size: 0.75em;

&#x20; --bs-badge-font-weight: 700;

&#x20; --bs-badge-color: #fff;

&#x20; --bs-badge-border-radius: var(--bs-border-radius);

&#x20; exibição: inline-block;

&#x20; preenchimento: var(--bs-badge-padding-y) var(--bs-badge-padding-x);

&#x20; tamanho-da-fonte: var(--bs-badge-font-size);

&#x20; peso-da-fonte: var(--bs-badge-font-weight);

&#x20; altura da linha: 1;

&#x20; cor: var(--bs-badge-color);

&#x20; alinhamento do texto: centralizado;

&#x20; espaço em branco: nowrap;

&#x20; alinhamento vertical: linha de base;

&#x20; raio da borda: var(--bs-badge-border-radius);

}

.badge:vazio {

&#x20; exibir: nenhum;

}



.btn .badge {

&#x20; posição: relativa;

&#x20; topo: -1px;

}



.alert {

&#x20; --bs-alert-bg: transparente;

&#x20; --bs-alert-padding-x: 1rem;

&#x20; --bs-alert-padding-y: 1rem;

&#x20; --bs-alert-margin-bottom: 1rem;

&#x20; --bs-alert-color: herdar;

&#x20; --bs-alert-border-color: transparente;

&#x20; --bs-alert-border: var(--bs-border-width) sólido var(--bs-alert-border-color);

&#x20; --bs-alert-border-radius: var(--bs-border-radius);

&#x20; --bs-alert-link-color: herdar;

&#x20; posição: relativa;

&#x20; preenchimento: var(--bs-alert-padding-y) var(--bs-alert-padding-x);

&#x20; margem inferior: var(--bs-alert-margin-bottom);

&#x20; cor: var(--bs-alert-color);

&#x20; cor de fundo: var(--bs-alert-bg);

&#x20; borda: var(--bs-alert-border);

&#x20; raio da borda: var(--bs-alert-border-radius);

}



.alert-heading {

&#x20; cor: herdar;

}



.alert-link {

&#x20; peso da fonte: 700;

&#x20; cor: var(--bs-alert-link-color);

}



.alert-dismissible {

&#x20; padding-right: 3rem;

}

.alert-dismissible .btn-close {

&#x20; posição: absoluta;

&#x20; topo: 0;

&#x20; direita: 0;

&#x20; Índice z: 2;

&#x20; preenchimento: 1,25rem 1rem;

}



.alert-primary {

&#x20; --bs-alert-color: var(--bs-primary-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-primary-bg-subtle);

&#x20; --bs-alert-border-color: var(--bs-primary-border-subtle);

&#x20; --bs-alert-link-color: var(--bs-primary-text-emphasis);

}



.alert-secondary {

&#x20; --bs-alert-color: var(--bs-secondary-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-secondary-bg-subtle);

&#x20; --bs-alert-border-color: var(--bs-secondary-border-subtle);

&#x20; --bs-alert-link-color: var(--bs-secondary-text-emphasis);

}



.alert-success {

&#x20; --bs-alert-color: var(--bs-success-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-success-bg-subtle);

&#x20; --bs-alert-border-color: var(--bs-success-border-subtle);

&#x20; --bs-alert-link-color: var(--bs-success-text-emphasis);

}



.alert-info {

&#x20; --bs-alert-color: var(--bs-info-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-info-bg-subtle);

&#x20; --bs-alert-border-color: var(--bs-info-border-subtle);

&#x20; --bs-alert-link-color: var(--bs-info-text-emphasis);

}



.alert-warning {

&#x20; --bs-alert-color: var(--bs-warning-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-warning-bg-subtle);

&#x20; --bs-alert-border-color: var(--bs-warning-border-subtle);

&#x20; --bs-alert-link-color: var(--bs-warning-text-emphasis);

}



.alert-danger {

&#x20; --bs-alert-color: var(--bs-danger-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-danger-bg-sutil);

&#x20; --bs-alert-border-color: var(--bs-danger-border-sutil);

&#x20; --bs-alert-link-color: var(--bs-danger-text-emphasis);

}



.alert-light {

&#x20; --bs-alert-color: var(--bs-light-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-light-bg-sutil);

&#x20; --bs-alert-border-color: var(--bs-light-border-subtle);

&#x20; --bs-alert-link-color: var(--bs-light-text-emphasis);

}



.alert-dark {

&#x20; --bs-alert-color: var(--bs-dark-text-emphasis);

&#x20; --bs-alert-bg: var(--bs-dark-bg-subtle);

&#x20; --bs-alert-border-color: var(--bs-dark-border-subtle);

&#x20; --bs-alert-link-color: var(--bs-dark-text-emphasis);

}



@keyframes barras-de-progresso {

&#x20; 0% {

&#x20;   background-position-x: 1rem;

&#x20; }

}

.progresso,

.progresso-empilhado {

&#x20; --bs-progress-height: 1rem;

&#x20; --bs-progress-font-size: 0.75rem;

&#x20; --bs-progress-bg: var(--bs-secondary-bg);

&#x20; --bs-progress-border-radius: var(--bs-border-radius);

&#x20; --bs-progress-box-shadow: var(--bs-box-shadow-inset);

&#x20; --bs-progress-bar-color: #fff;

&#x20; --bs-progress-bar-bg: #0d6efd;

&#x20; --bs-progress-bar-transition: largura 0.6s ease;

&#x20; Exibir: flexível;

&#x20; altura: var(--bs-progress-height);

&#x20; overflow: oculto;

&#x20; tamanho-da-fonte: var(--bs-progress-font-size);

&#x20; cor de fundo: var(--bs-progress-bg);

&#x20; raio da borda: var(-bs-progress-border-radius);

}



.progress-bar {

&#x20; Exibir: flexível;

&#x20; flex-direction: coluna;

&#x20; justificar-conteúdo: centralizado;

&#x20; overflow: oculto;

&#x20; cor: var(--bs-progress-bar-color);

&#x20; alinhamento do texto: centralizado;

&#x20; espaço em branco: nowrap;

&#x20; cor de fundo: var(--bs-progress-bar-bg);

&#x20; transição: var(--bs-progress-bar-transition);

}

@media (prefers-reduced-motion: reduce) {

&#x20; .progress-bar {

&#x20;   transição: nenhuma;

&#x20; }

}



.progress-bar-listrada {

&#x20; background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);

&#x20; background-size: var(--bs-progress-height) var(--bs-progress-height);

}



.progress-stacked > .progress {

&#x20; transbordamento: visível;

}



.progress-stacked > .progress > .progress-bar {

&#x20; largura: 100%;

}



.progress-bar-animated {

&#x20; animação: listras de barra de progresso linear infinita de 1 segundo;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .progress-bar-animated {

&#x20;   Animação: nenhuma;

&#x20; }

}



.list-group {

&#x20; --bs-list-group-color: var(--bs-body-color);

&#x20; --bs-list-group-bg: var(--bs-body-bg);

&#x20; --bs-list-group-border-color: var(--bs-border-color);

&#x20; --bs-list-group-border-width: var(--bs-border-width);

&#x20; --bs-list-group-border-radius: var(--bs-border-radius);

&#x20; --bs-list-group-item-padding-x: 1rem;

&#x20; --bs-list-group-item-padding-y: 0.5rem;

&#x20; --bs-list-group-action-color: var(--bs-secondary-color);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-tertiary-bg);

&#x20; --bs-list-group-action-active-color: var(--bs-body-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-secondary-bg);

&#x20; --bs-list-group-disabled-color: var(--bs-secondary-color);

&#x20; --bs-list-group-disabled-bg: var(--bs-body-bg);

&#x20; --bs-list-group-active-color: #fff;

&#x20; --bs-list-group-active-bg: #0d6efd;

&#x20; --bs-list-group-active-border-color: #0d6efd;

&#x20; Exibir: flexível;

&#x20; flex-direction: coluna;

&#x20; preenchimento-esquerdo: 0;

&#x20; margem-inferior: 0;

&#x20; raio-da-borda: var(--bs-list-group-border-radius);

}



.lista-grupo-numerado {

&#x20; list-style-type: none;

&#x20; reinicialização do contador: seção;

}

.list-group-numbered > .list-group-item::before {

&#x20; conteúdo: contadores(seção, ".") ". ";

&#x20; contador-incremento: seção;

}



.list-group-item-action {

&#x20; largura: 100%;

&#x20; cor: var(--bs-list-group-action-color);

&#x20; alinhamento de texto: herdar;

}

.list-group-item-action:hover, .list-group-item-action:focus {

&#x20; Índice z: 1;

&#x20; cor: var(--bs-list-group-action-hover-color);

&#x20; decoração de texto: nenhuma;

&#x20; cor de fundo: var(--bs-list-group-action-hover-bg);

}

.list-group-item-action:active {

&#x20; cor: var(--bs-list-group-action-active-color);

&#x20; cor de fundo: var(--bs-list-group-action-active-bg);

}



.list-group-item {

&#x20; posição: relativa;

&#x20; exibir: bloco;

&#x20; preenchimento: var(--bs-list-group-item-padding-y) var(--bs-list-group-item-padding-x);

&#x20; cor: var(--bs-list-group-color);

&#x20; decoração de texto: nenhuma;

&#x20; cor de fundo: var(--bs-list-group-bg);

&#x20; borda: var(--bs-list-group-border-width) sólida var(--bs-list-group-border-color);

}

.list-group-item:first-child {

&#x20; raio-superior-esquerdo-da-borda: herdar;

&#x20; raio-superior-direito-da-borda: herdar;

}

.list-group-item:last-child {

&#x20; raio-inferior-direito-da-borda: herdar;

&#x20; raio-inferior-esquerdo-da-borda: herdar;

}

.list-group-item.disabled, .list-group-item:disabled {

&#x20; cor: var(--bs-list-group-disabled-color);

&#x20; eventos-ponteiro: nenhum;

&#x20; cor de fundo: var(--bs-list-group-disabled-bg);

}

.list-group-item.active {

&#x20; Índice z: 2;

&#x20; cor: var(--bs-list-group-active-color);

&#x20; cor de fundo: var(--bs-list-group-active-bg);

&#x20; cor-da-borda: var(--bs-list-group-active-border-color);

}

.list-group-item + .list-group-item {

&#x20; largura-superior-da-borda: 0;

}

.list-group-item + .list-group-item.active {

&#x20; margem-superior: calc(-1 \* var(--bs-list-group-border-width));

&#x20; largura-superior-da-borda: var(--bs-list-group-border-width);

}



.list-group-horizontal {

&#x20; flex-direction: linha;

}

.list-group-horizontal > .list-group-item:first-child:not(:last-child) {

&#x20; raio-borda-inferior-esquerda: var(--bs-list-group-border-radius);

&#x20; raio-superior-direito-da-borda: 0;

}

.list-group-horizontal > .list-group-item:last-child:not(:first-child) {

&#x20; raio-borda-superior-direita: var(--bs-list-group-border-radius);

&#x20; raio-da-borda-inferior-esquerda: 0;

}

.list-group-horizontal > .list-group-item.active {

&#x20; margem superior: 0;

}

.list-group-horizontal > .list-group-item + .list-group-item {

&#x20; largura-superior-da-borda: var(--bs-list-group-border-width);

&#x20; largura-esquerda-da-borda: 0;

}

.list-group-horizontal > .list-group-item + .list-group-item.active {

&#x20; margem-esquerda: calc(-1 \* var(--bs-list-group-border-width));

&#x20; largura-da-borda-esquerda: var(--bs-list-group-border-width);

}



@media (min-width: 576px) {

&#x20; .list-group-horizontal-sm {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .list-group-horizontal-sm > .list-group-item:first-child:not(:last-child) {

&#x20;   raio-borda-inferior-esquerda: var(--bs-list-group-border-radius);

&#x20;   raio-superior-direito-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-sm > .list-group-item:last-child:not(:first-child) {

&#x20;   raio-borda-superior-direita: var(--bs-list-group-border-radius);

&#x20;   raio-da-borda-inferior-esquerda: 0;

&#x20; }

&#x20; .list-group-horizontal-sm > .list-group-item.active {

&#x20;   margem superior: 0;

&#x20; }

&#x20; .list-group-horizontal-sm > .list-group-item + .list-group-item {

&#x20;   largura-superior-da-borda: var(--bs-list-group-border-width);

&#x20;   largura-esquerda-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-sm > .list-group-item + .list-group-item.active {

&#x20;   margem-esquerda: calc(-1 \* var(--bs-list-group-border-width));

&#x20;   largura-da-borda-esquerda: var(--bs-list-group-border-width);

&#x20; }

}

@media (min-width: 768px) {

&#x20; .list-group-horizontal-md {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .list-group-horizontal-md > .list-group-item:first-child:not(:last-child) {

&#x20;   raio-borda-inferior-esquerda: var(--bs-list-group-border-radius);

&#x20;   raio-superior-direito-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-md > .list-group-item:last-child:not(:first-child) {

&#x20;   raio-borda-superior-direita: var(--bs-list-group-border-radius);

&#x20;   raio-da-borda-inferior-esquerda: 0;

&#x20; }

&#x20; .list-group-horizontal-md > .list-group-item.active {

&#x20;   margem superior: 0;

&#x20; }

&#x20; .list-group-horizontal-md > .list-group-item + .list-group-item {

&#x20;   largura-superior-da-borda: var(--bs-list-group-border-width);

&#x20;   largura-esquerda-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-md > .list-group-item + .list-group-item.active {

&#x20;   margem-esquerda: calc(-1 \* var(--bs-list-group-border-width));

&#x20;   largura-da-borda-esquerda: var(--bs-list-group-border-width);

&#x20; }

}

@media (min-width: 992px) {

&#x20; .list-group-horizontal-lg {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .list-group-horizontal-lg > .list-group-item:first-child:not(:last-child) {

&#x20;   raio-borda-inferior-esquerda: var(--bs-list-group-border-radius);

&#x20;   raio-superior-direito-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-lg > .list-group-item:last-child:not(:first-child) {

&#x20;   raio-borda-superior-direita: var(--bs-list-group-border-radius);

&#x20;   raio-da-borda-inferior-esquerda: 0;

&#x20; }

&#x20; .list-group-horizontal-lg > .list-group-item.active {

&#x20;   margem superior: 0;

&#x20; }

&#x20; .list-group-horizontal-lg > .list-group-item + .list-group-item {

&#x20;   largura-superior-da-borda: var(--bs-list-group-border-width);

&#x20;   largura-esquerda-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-lg > .list-group-item + .list-group-item.active {

&#x20;   margem-esquerda: calc(-1 \* var(--bs-list-group-border-width));

&#x20;   largura-da-borda-esquerda: var(--bs-list-group-border-width);

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .list-group-horizontal-xl {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .list-group-horizontal-xl > .list-group-item:first-child:not(:last-child) {

&#x20;   raio-borda-inferior-esquerda: var(--bs-list-group-border-radius);

&#x20;   raio-superior-direito-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-xl > .list-group-item:last-child:not(:first-child) {

&#x20;   raio-borda-superior-direita: var(--bs-list-group-border-radius);

&#x20;   raio-da-borda-inferior-esquerda: 0;

&#x20; }

&#x20; .list-group-horizontal-xl > .list-group-item.active {

&#x20;   margem superior: 0;

&#x20; }

&#x20; .list-group-horizontal-xl > .list-group-item + .list-group-item {

&#x20;   largura-superior-da-borda: var(--bs-list-group-border-width);

&#x20;   largura-esquerda-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-xl > .list-group-item + .list-group-item.active {

&#x20;   m argin-left: calc(-1 \* var(--bs-list-group-border-width));

&#x20;   largura-da-borda-esquerda: var(--bs-list-group-border-width);

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .list-group-horizontal-xxl {

&#x20;   flex-direction: linha;

&#x20; }

&#x20; .list-group-horizontal-xxl > .list-group-item:first-child:not(:last-child) {

&#x20;   raio-borda-inferior-esquerda: var(--bs-list-group-border-radius);

&#x20;   raio-superior-direito-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-xxl > .list-group-item:last-child:not(:first-child) {

&#x20;   raio-borda-superior-direita: var(--bs-list-group-border-radius);

&#x20;   raio-da-borda-inferior-esquerda: 0;

&#x20; }

&#x20; .list-group-horizontal-xxl > .list-group-item.active {

&#x20;   margem superior: 0;

&#x20; }

&#x20; .list-group-horizontal-xxl > .list-group-item + .list-group-item {

&#x20;   largura-superior-da-borda: var(--bs-list-group-border-width);

&#x20;   largura-esquerda-da-borda: 0;

&#x20; }

&#x20; .list-group-horizontal-xxl > .list-group-item + .list-group-item.active {

&#x20;   margem-esquerda: calc(-1 \* var(--bs-list-group-border-width));

&#x20;   largura-da-borda-esquerda: var(--bs-list-group-border-width);

&#x20; }

}

.lista-grupo-flush {

&#x20; raio-da-borda: 0;

}

.list-group-flush > .list-group-item {

&#x20; largura-da-borda: 0 0 var(--bs-list-group-border-width);

}

.list-group-flush > .list-group-item:last-child {

&#x20; largura-inferior-da-borda: 0;

}



.list-group-item-primary {

&#x20; --bs-list-group-color: var(--bs-primary-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-primary-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-primary-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-primary-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-primary-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-primary-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-primary-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-primary-text-emphasis);

}



.list-group-item-secondary {

&#x20; --bs-list-group-color: var(--bs-secondary-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-secondary-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-secondary-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-secondary-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-secondary-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-secondary-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-secondary-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-secondary-text-emphasis);

}



.list-group-item-success {

&#x20; --bs-list-group-color: var(--bs-success-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-success-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-success-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-success-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-success-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-success-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-success-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-success-text-emphasis);

}



.list-group-item-info {

&#x20; --bs-list-group-color: var(--bs-info-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-info-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-info-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-info-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-info-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-info-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-info-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-info-text-emphasis);

}



.list-group-item-warning {

&#x20; --bs-list-group-color: var(--bs-warning-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-warning-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-warning-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-warning-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-warning-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-warning-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-warning-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-warning-text-emphasis);

}



.list-group-item-danger {

&#x20; --bs-list-group-color: var(--bs-danger-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-danger-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-danger-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-danger-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-danger-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-danger-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-danger-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-danger-text-emphasis);

}



.list-group-item-light {

&#x20; --bs-list-group-color: var(--bs-light-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-light-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-light-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-light-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-light-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-light-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-light-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-light-text-emphasis);

}



.list-group-item-dark {

&#x20; --bs-list-group-color: var(--bs-dark-text-emphasis);

&#x20; --bs-list-group-bg: var(--bs-dark-bg-subtle);

&#x20; --bs-list-group-border-color: var(--bs-dark-border-subtle);

&#x20; --bs-list-group-action-hover-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-hover-bg: var(--bs-dark-border-subtle);

&#x20; --bs-list-group-action-active-color: var(--bs-emphasis-color);

&#x20; --bs-list-group-action-active-bg: var(--bs-dark-border-subtle);

&#x20; --bs-list-group-active-color: var(--bs-dark-bg-subtle);

&#x20; --bs-list-group-active-bg: var(--bs-dark-text-emphasis);

&#x20; --bs-list-group-active-border-color: var(--bs-dark-text-emphasis);

}



.btn-close {

&#x20; --bs-btn-close-color: #000;

&#x20; --bs-btn-close-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23000'%3e%3cpath d='M.293.293a1 1 0 0 1 1.414 0L8 6.586 14.293.293a1 1 0 1 1 1.414 1.414L9.414 8l6.293 6.293a1 1 0 0 1-1.414 1.414L8 9.414l-6.293 6.293a1 1 0 0 1-1.414-1.414L6.586 8 .293 1.707a1 1 0 0 1 0-1.414z'/%3e%3c/svg%3e");

&#x20; --bs-btn-close-opacity: 0.5;

&#x20; --bs-btn-close-hover-opacity: 0.75;

&#x20; --bs-btn-close-focus-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);

&#x20; --bs-btn-close-focus-opacity: 1;

&#x20; --bs-btn-close-disabled-opacity: 0.25;

&#x20; --bs-btn-close-white-filter: inverter(1) escala de cinza(100%) brilho(200%);

&#x20; box-sized: content-box;

&#x20; largura: 1em;

&#x20; altura: 1em;

&#x20; preenchimento: 0,25em 0,25em;

&#x20; cor: var(--bs-btn-close-color);

&#x20; fundo: transparente var(--bs-btn-close-bg) centro/1em automático sem repetição;

&#x20; borda: 0;

&#x20; raio-da-borda: 0,375rem;

&#x20; opacidade: var(--bs-btn-close-opacity);

}

.btn-close:hover {

&#x20; cor: var(--bs-btn-close-color);

&#x20; decoração de texto: nenhuma;

&#x20; opacidade: var(--bs-btn-close-hover-opacity);

}

.btn-close:focus {

&#x20; esboço: 0;

&#x20; box-shadow: var(--bs-btn-close-focus-shadow);

&#x20; opacidade: var(--bs-btn-close-focus-opacity);

}

.btn-close:disabled, .btn-close.disabled {

&#x20; eventos-ponteiro: nenhum;

&#x20; -webkit-user-select: nenhum;

&#x20; -moz-user-select: nenhum;

&#x20; seleção do usuário: nenhuma;

&#x20; opacidade: var(--bs-btn-close-disabled-opacity);

}



.btn-close-white {

&#x20; filtro: var(--bs-btn-close-white-filter);

}



\[data-bs-theme=dark] .btn-close {

&#x20; filtro: var(--bs-btn-close-white-filter);

}



.brinde {

&#x20; --bs-toast-zindex: 1090;

&#x20; --bs-toast-padding-x: 0.75rem;

&#x20; --bs-toast-padding-y: 0.5rem;

&#x20; --bs-toast-spacing: 1.5rem;

&#x20; --bs-toast-max-width: 350px;

&#x20; --bs-toast-font-size: 0.875rem;

&#x20; --bs-toast-color: ;

&#x20; --bs-toast-bg: rgba(var(--bs-body-bg-rgb), 0,85);

&#x20; --bs-toast-border-width: var(--bs-border-width);

&#x20; --bs-toast-border-color: var(--bs-border-color-translucent);

&#x20; --bs-toast-border-radius: var(--bs-border-radius);

&#x20; --bs-toast-box-shadow: var(--bs-box-shadow);

&#x20; --bs-toast-header-color: var(--bs-secondary-color);

&#x20; --bs-toast-header-bg: rgba(var(--bs-body-bg-rgb), 0,85);

&#x20; --bs-toast-header-border-color: var(--bs-border-color-translucent);

&#x20; largura: var(--bs-toast-max-width);

&#x20; largura máxima: 100%;

&#x20; tamanho-da-fonte: var(--bs-toast-font-size);

&#x20; cor: var(--bs-toast-color);

&#x20; eventos-ponteiro: automático;

&#x20; cor de fundo: var(--bs-toast-bg);

&#x20; background-clip: padding-box;

&#x20; borda: var(--bs-toast-border-width) var sólido(--bs-toast-border-color);

&#x20; box-shadow: var(--bs-toast-box-shadow);

&#x20; raio da borda: var(-bs-toast-border-radius);

}

.toast.mostrando {

&#x20; opacidade: 0;

}

.toast:não(.show) {

&#x20; exibir: nenhum;

}



.toast-container {

&#x20; --bs-toast-zindex: 1090;

&#x20; posição: absoluta;

&#x20; z-index: var(--bs-toast-zindex);

&#x20; largura: -webkit-max-content;

&#x20; largura: -moz-max-content;

&#x20; largura: conteúdo máximo;

&#x20; largura máxima: 100%;

&#x20; eventos-ponteiro: nenhum;

}

.toast-container > :not(:last-child) {

&#x20; margem inferior: var(-bs-toast-spacing);

}



.toast-header {

&#x20; Exibir: flexível;

&#x20; alinhamento-itens: centro;

&#x20; preenchimento: var(--bs-toast-padding-y) var(--bs-toast-padding-x);

&#x20; cor: var(--bs-toast-header-color);

&#x20; cor de fundo: var(--bs-toast-header-bg);

&#x20; background-clip: padding-box;

&#x20; borda inferior: var(--bs-toast-border-width) var sólido(--bs-toast-header-border-color);

&#x20; raio-borda-superior-esquerda: calc(var(--bs-toast-border-radius) - var(--bs-toast-border-width));

&#x20; raio-topo-direito-da-borda: calc(var(--bs-toast-border-radius) - var(--bs-toast-border-width));

}

.toast-header .btn-close {

&#x20; margem-direita: calc(-0.5 \* var(--bs-toast-padding-x));

&#x20; margem-esquerda: var(--bs-toast-padding-x);

}



.toast-body {

&#x20; preenchimento: var(--bs-toast-padding-x);

&#x20; quebra-de-palavra: quebra-de-palavra;

}



.modal {

&#x20; --bs-modal-zindex: 1055;

&#x20; --bs-modal-width: 500px;

&#x20; --bs-modal-padding: 1rem;

&#x20; --bs-modal-margin: 0.5rem;

&#x20; --bs-modal-color: ;

&#x20; --bs-modal-bg: var(--bs-body-bg);

&#x20; --bs-modal-border-color: var(--bs-border-color-translucent);

&#x20; --bs-modal-border-width: var(--bs-border-width);

&#x20; --bs-modal-border-radius: var(--bs-border-radius-lg);

&#x20; --bs-modal-box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);

&#x20; --bs-modal-inner-border-radius: calc(var(--bs-border-radius-lg) - (var(--bs-border-width)));

&#x20; --bs-modal-header-padding-x: 1rem;

&#x20; --bs-modal-header-padding-y: 1rem;

&#x20; --bs-modal-header-padding: 1rem 1rem;

&#x20; --bs-modal-header-border-color: var(--bs-border-color);

&#x20; --bs-modal-header-border-width: var(--bs-border-width);

&#x20; --bs-modal-title-line-height: 1.5;

&#x20; --bs-modal-footer-gap: 0.5rem;

&#x20; --bs-modal-footer-bg: ;

&#x20; --bs-modal-footer-border-color: var(--bs-border-color);

&#x20; --bs-modal-footer-border-width: var(--bs-border-width);

&#x20; posição: fixa;

&#x20; topo: 0;

&#x20; esquerda: 0;

&#x20; índice z: var(--bs-modal-zindex);

&#x20; exibir: nenhum;

&#x20; largura: 100%;

&#x20; altura: 100%;

&#x20; overflow-x: oculto;

&#x20; overflow-y: automático;

&#x20; esboço: 0;

}



.modal-dialog {

&#x20; posição: relativa;

&#x20; largura: automática;

&#x20; margem: var(--bs-modal-margin);

&#x20; eventos-ponteiro: nenhum;

}

.modal.fade .modal-dialog {

&#x20; transição: transformar 0,3s suavização de saída;

&#x20; transformar: traduzir(0, -50px);

}

@media (prefers-reduced-motion: reduce) {

&#x20; .modal.fade .modal-dialog {

&#x20;   transição: nenhuma;

&#x20; }

}

.modal.show .modal-dialog {

&#x20; transformar: nenhuma;

}

.modal.modal-static .modal-dialog {

&#x20; transformar: escala(1.02);

}



.modal-dialog-scrollable {

&#x20; altura: calc(100% - var(--bs-modal-margin) \* 2);

}

.modal-dialog-scrollable .modal-content {

&#x20; altura máxima: 100%;

&#x20; overflow: oculto;

}

.modal-dialog-scrollable .modal-body {

&#x20; overflow-y: automático;

}



.modal-dialog-centered {

&#x20; Exibir: flexível;

&#x20; alinhamento-itens: centro;

&#x20; altura mínima: calc(100% - var(--bs-modal-margin) \* 2);

}



.modal-content {

&#x20; posição: relativa;

&#x20; Exibir: flexível;

&#x20; flex-direction: coluna;

&#x20; largura: 100%;

&#x20; cor: var(--bs-modal-color);

&#x20; eventos-ponteiro: automático;

&#x20; cor de fundo: var(--bs-modal-bg);

&#x20; background-clip: padding-box;

&#x20; borda: var(--bs-modal-border-width) var sólido(--bs-modal-border-color);

&#x20; raio da borda: var(-bs-modal-border-radius);

&#x20; esboço: 0;

}



.modal-backdrop {

&#x20; --bs-backdrop-zindex: 1050;

&#x20; --bs-backdrop-bg: #000;

&#x20; --bs-backdrop-opacity: 0.5;

&#x20; posição: fixa;

&#x20; topo: 0;

&#x20; esquerda: 0;

&#x20; z-index: var(--bs-backdrop-zindex);

&#x20; largura: 100vw;

&#x20; altura: 100vh;

&#x20; cor de fundo: var(--bs-backdrop-bg);

}

.modal-backdrop.fade {

&#x20; opacidade: 0;

}

.modal-backdrop.show {

&#x20; opacidade: var(--bs-backdrop-opacity);

}



.modal-header {

&#x20; Exibir: flexível;

&#x20; flex-shrink: 0;

&#x20; alinhamento-itens: centro;

&#x20; justify-content: espaço-entre;

&#x20; preenchimento: var(--bs-modal-header-padding);

&#x20; borda inferior: var(--bs-modal-header-border-width) sólido var(--bs-modal-header-border-color);

&#x20; raio-borda-superior-esquerda: var(--bs-modal-inner-border-radius);

&#x20; raio-topo-direito-da-borda: var(--bs-modal-inner-border-radius);

}

.modal-header .btn-close {

&#x20; preenchimento: calc(var(--bs-modal-header-padding-y) \* 0.5) calc(var(--bs-modal-header-padding-x) \* 0.5);

&#x20; margem: calc(-0.5 \* var(--bs-modal-header-padding-y)) calc(-0.5 \* var(--bs-modal-header-padding-x)) calc(-0.5 \* var(--bs-modal-header-padding-y)) auto;

}



.modal-title {

&#x20; margem-inferior: 0;

&#x20; altura-da-linha: var(--bs-modal-title-line-height);

}



.modal-body {

&#x20; posição: relativa;

&#x20; flex: 1 1 auto;

&#x20; preenchimento: var(--bs-modal-padding);

}



.modal-footer {

&#x20; Exibir: flexível;

&#x20; flex-shrink: 0;

&#x20; flex-wrap: envolver;

&#x20; alinhamento-itens: centro;

&#x20; justify-content: flex-end;

&#x20; preenchimento: calc(var(--bs-modal-padding) - var(--bs-modal-footer-gap) \* 0.5);

&#x20; cor de fundo: var(--bs-modal-footer-bg);

&#x20; borda superior: var(--bs-modal-footer-border-width) sólido var(--bs-modal-footer-border-color);

&#x20; raio-borda-inferior-direita: var(--bs-modal-inner-border-radius);

&#x20; raio-borda-inferior-esquerda: var(--bs-modal-inner-border-radius);

}

.modal-footer > \* {

&#x20; margem: calc(var(--bs-modal-footer-gap) \* 0,5);

}



@media (min-width: 576px) {

&#x20; .modal {

&#x20;   --bs-modal-margin: 1.75rem;

&#x20;   --bs-modal-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);

&#x20; }

&#x20; .modal-dialog {

&#x20;   largura-máxima: var(--bs-modal-width);

&#x20;   margem-direita: automática;

&#x20;   margem-esquerda: automática;

&#x20; }

&#x20; .modal-sm {

&#x20;   --bs-modal-width: 300px;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .modal-lg,

&#x20; .modal-xl {

&#x20;   --bs-modal-width: 800px;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .modal-xl {

&#x20;   --bs-modal-width: 1140px;

&#x20; }

}

.modal-fullscreen {

&#x20; largura: 100vw;

&#x20; largura-máxima: nenhuma;

&#x20; altura: 100%;

&#x20; margem: 0;

}

.modal-fullscreen .modal-content {

&#x20; altura: 100%;

&#x20; borda: 0;

&#x20; raio-da-borda: 0;

}

.modal-fullscreen .modal-header,

.modal-fullscreen .modal-footer {

&#x20; raio-da-borda: 0;

}

.modal-fullscreen .modal-body {

&#x20; overflow-y: automático;

}



@media (max-width: 575.98px) {

&#x20; .modal-fullscreen-sm-down {

&#x20;   largura: 100vw;

&#x20;   largura-máxima: nenhuma;

&#x20;   altura: 100%;

&#x20;   margem: 0;

&#x20; }

&#x20; .modal-fullscreen-sm-down .modal-content {

&#x20;   altura: 100%;

&#x20;   borda: 0;

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-sm-down .modal-header,

&#x20; .modal-fullscreen-sm-down .modal-footer {

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-sm-down .modal-body {

&#x20;   overflow-y: automático;

&#x20; }

}

@media (max-width: 767.98px) {

&#x20; .modal-fullscreen-md-down {

&#x20;   largura: 100vw;

&#x20;   largura-máxima: nenhuma;

&#x20;   altura: 100%;

&#x20;   margem: 0;

&#x20; }

&#x20; .modal-fullscreen-md-down .modal-content {

&#x20;   altura: 100%;

&#x20;   borda: 0;

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-md-down .modal-header,

&#x20; .modal-fullscreen-md-down .modal-footer {

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-md-down .modal-body {

&#x20;   overflow-y: automático;

&#x20; }

}

@media (max-width: 991.98px) {

&#x20; .modal-fullscreen-lg-down {

&#x20;   largura: 100vw;

&#x20;   largura-máxima: nenhuma;

&#x20;   altura: 100%;

&#x20;   margem: 0;

&#x20; }

&#x20; .modal-fullscreen-lg-down .modal-content {

&#x20;   altura: 100%;

&#x20;   borda: 0;

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-lg-down .modal-header,

&#x20; .modal-fullscreen-lg-down .modal-footer {

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-lg-down .modal-body {

&#x20;   overflow-y: automático;

&#x20; }

}

@media (max-width: 1199.98px) {

&#x20; .modal-fullscreen-xl-down {

&#x20;   largura: 100vw;

&#x20;   largura-máxima: nenhuma;

&#x20;   altura: 100%;

&#x20;   margem: 0;

&#x20; }

&#x20; .modal-fullscreen-xl-down .modal-content {

&#x20;   altura: 100%;

&#x20;   borda: 0;

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-xl-down .modal-header,

&#x20; .modal-fullscreen-xl-down .modal-footer {

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-xl-down .modal-body {

&#x20;   overflow-y: automático;

&#x20; }

}

@media (max-width: 1399.98px) {

&#x20; .modal-fullscreen-xxl-down {

&#x20;   largura: 100vw;

&#x20;   largura-máxima: nenhuma;

&#x20;   altura: 100%;

&#x20;   margem: 0;

&#x20; }

&#x20; .modal-fullscreen-xxl-down .modal-content {

&#x20;   altura: 100%;

&#x20;   borda: 0;

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-xxl-down .modal-header,

&#x20; .modal-fullscreen-xxl-down .modal-footer {

&#x20;   raio-da-borda: 0;

&#x20; }

&#x20; .modal-fullscreen-xxl-down .modal-body {

&#x20;   overflow-y: automático;

&#x20; }

}

.tooltip {

&#x20; --bs-tooltip-zindex: 1080;

&#x20; --bs-tooltip-max-width: 200px;

&#x20; --bs-tooltip-padding-x: 0.5rem;

&#x20; --bs-tooltip-padding-y: 0.25rem;

&#x20; --bs-tooltip-margin: ;

&#x20; --bs-tooltip-font-size: 0.875rem;

&#x20; --bs-tooltip-color: var(--bs-body-bg);

&#x20; --bs-tooltip-bg: var(--bs-emphasis-color);

&#x20; --bs-tooltip-border-radius: var(--bs-border-radius);

&#x20; --bs-tooltip-opacity: 0.9;

&#x20; --bs-tooltip-arrow-width: 0.8rem;

&#x20; --bs-tooltip-arrow-height: 0.4rem;

&#x20; z-index: var(--bs-tooltip-zindex);

&#x20; exibir: bloco;

&#x20; margem: var(--bs-tooltip-margin);

&#x20; família de fontes: var(--bs-font-sans-serif);

&#x20; estilo-da-fonte: normal;

&#x20; peso da fonte: 400;

&#x20; altura da linha: 1,5;

&#x20; alinhamento de texto: esquerda;

&#x20; alinhamento de texto: início;

&#x20; decoração de texto: nenhuma;

&#x20; sombra-texto: nenhuma;

&#x20; transformação de texto: nenhuma;

&#x20; espaçamento entre letras: normal;

&#x20; quebra de palavra: normal;

&#x20; Espaço em branco: normal;

&#x20; Espaçamento entre palavras: normal;

&#x20; quebra-linha: automática;

&#x20; tamanho-da-fonte: var(--bs-tooltip-font-size);

&#x20; quebra-de-palavra: quebra-de-palavra;

&#x20; opacidade: 0;

}

.tooltip.show {

&#x20; opacidade: var(--bs-tooltip-opacity);

}

.tooltip .tooltip-seta {

&#x20; exibir: bloco;

&#x20; largura: var(--bs-tooltip-arrow-width);

&#x20; altura: var(--bs-tooltip-arrow-height);

}

.tooltip .tooltip-arrow::before {

&#x20; posição: absoluta;

&#x20; contente: "";

&#x20; cor da borda: transparente;

&#x20; estilo da borda: sólida;

}



.bs-tooltip-top .tooltip-arrow, .bs-tooltip-auto\[data-popper-placement^=top] .tooltip-arrow {

&#x20; inferior: calc(-1 \* var(--bs-tooltip-arrow-height));

}

.bs-tooltip-top .tooltip-arrow::before, .bs-tooltip-auto\[data-popper-placement^=top] .tooltip-arrow::before {

&#x20; topo: -1px;

&#x20; largura-da-borda: var(--bs-tooltip-arrow-height) calc(var(--bs-tooltip-arrow-width) \* 0.5) 0;

&#x20; cor-borda-superior: var(--bs-tooltip-bg);

}



/\* rtl:begin:ignore \*/

.bs-tooltip-end .tooltip-arrow, .bs-tooltip-auto\[data-popper-placement^=right] .tooltip-arrow {

&#x20; esquerda: calc(-1 \* var(--bs-tooltip-arrow-height));

&#x20; largura: var(--bs-tooltip-arrow-height);

&#x20; altura: var(--bs-tooltip-arrow-width);

}

.bs-tooltip-end .tooltip-arrow::before, .bs-tooltip-auto\[data-popper-placement^=right] .tooltip-arrow::before {

&#x20; direita: -1px;

&#x20; largura-da-borda: calc(var(--bs-tooltip-arrow-width) \* 0.5) var(--bs-tooltip-arrow-height) calc(var(--bs-tooltip-arrow-width) \* 0.5) 0;

&#x20; cor-da-borda-direita: var(--bs-tooltip-bg);

}



/\* rtl:end:ignore \*/

.bs-tooltip-bottom .tooltip-arrow, .bs-tooltip-auto\[data-popper-placement^=bottom] .tooltip-arrow {

&#x20; topo: calc(-1 \* var(--bs-tooltip-arrow-height));

}

.bs-tooltip-bottom .tooltip-arrow::before, .bs-tooltip-auto\[data-popper-placement^=bottom] .tooltip-arrow::before {

&#x20; inferior: -1px;

&#x20; largura-da-borda: 0 calc(var(--bs-tooltip-arrow-width) \* 0.5) var(--bs-tooltip-arrow-height);

&#x20; cor-borda-inferior: var(--bs-tooltip-bg);

}



/\* rtl:begin:ignore \*/

.bs-tooltip-start .tooltip-arrow, .bs-tooltip-auto\[data-popper-placement^=left] .tooltip-arrow {

&#x20; direita: calc(-1 \* var(--bs-tooltip-arrow-height));

&#x20; largura: var(--bs-tooltip-arrow-height);

&#x20; altura: var(--bs-tooltip-arrow-width);

}

.bs-tooltip-start .tooltip-arrow::before, .bs-tooltip-auto\[data-popper-placement^=left] .tooltip-arrow::before {

&#x20; esquerda: -1px;

&#x20; largura-da-borda: calc(var(--bs-tooltip-arrow-width) \* 0.5) 0 calc(var(--bs-tooltip-arrow-width) \* 0.5) var(--bs-tooltip-arrow-height);

&#x20; cor-da-borda-esquerda: var(--bs-tooltip-bg);

}



/\* rtl:end:ignore \*/

.tooltip-inner {

&#x20; largura-máxima: var(--bs-tooltip-max-width);

&#x20; preenchimento: var(--bs-tooltip-padding-y) var(--bs-tooltip-padding-x);

&#x20; cor: var(--bs-tooltip-color);

&#x20; alinhamento do texto: centralizado;

&#x20; cor de fundo: var(--bs-tooltip-bg);

&#x20; raio da borda: var(-bs-tooltip-border-radius);

}



.popover {

&#x20; --bs-popover-zindex: 1070;

&#x20; --bs-popover-max-width: 276px;

&#x20; --bs-popover-font-size: 0.875rem;

&#x20; --bs-popover-bg: var(--bs-body-bg);

&#x20; --bs-popover-border-width: var(--bs-border-width);

&#x20; --bs-popover-border-color: var(--bs-border-color-translucent);

&#x20; --bs-popover-border-radius: var(--bs-border-radius-lg);

&#x20; --bs-popover-inner-border-radius: calc(var(--bs-border-radius-lg) - var(--bs-border-width));

&#x20; --bs-popover-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);

&#x20; --bs-popover-header-padding-x: 1rem;

&#x20; --bs-popover-header-padding-y: 0.5rem;

&#x20; --bs-popover-header-font-size: 1rem;

&#x20; --bs-popover-header-color: herdar;

&#x20; --bs-popover-header-bg: var(--bs-secondary-bg);

&#x20; --bs-popover-body-padding-x: 1rem;

&#x20; --bs-popover-body-padding-y: 1rem;

&#x20; --bs-popover-body-color: var(--bs-body-color);

&#x20; --bs-popover-arrow-width: 1rem;

&#x20; --bs-popover-arrow-height: 0.5rem;

&#x20; --bs-popover-arrow-border: var(--bs-popover-border-color);

&#x20; z-index: var(--bs-popover-zindex);

&#x20; exibir: bloco;

&#x20; largura-máxima: var(--bs-popover-max-width);

&#x20; família de fontes: var(--bs-font-sans-serif);

&#x20; estilo-da-fonte: normal;

&#x20; peso da fonte: 400;

&#x20; altura da linha: 1,5;

&#x20; alinhamento de texto: esquerda;

&#x20; alinhamento de texto: início;

&#x20; decoração de texto: nenhuma;

&#x20; sombra-texto: nenhuma;

&#x20; transformação de texto: nenhuma;

&#x20; espaçamento entre letras: normal;

&#x20; quebra de palavra: normal;

&#x20; Espaço em branco: normal;

&#x20; Espaçamento entre palavras: normal;

&#x20; quebra-linha: automática;

&#x20; tamanho-da-fonte: var(--bs-popover-font-size);

&#x20; quebra-de-palavra: quebra-de-palavra;

&#x20; cor de fundo: var(--bs-popover-bg);

&#x20; background-clip: padding-box;

&#x20; borda: var(--bs-popover-border-width) var sólido(--bs-popover-border-color);

&#x20; raio da borda: var(-bs-popover-border-radius);

}

.popover .popover-arrow {

&#x20; exibir: bloco;

&#x20; largura: var(--bs-popover-arrow-width);

&#x20; altura: var(--bs-popover-arrow-height);

}

.popover .popover-arrow::before, .popover .popover-arrow::after {

&#x20; posição: absoluta;

&#x20; exibir: bloco;

&#x20; contente: "";

&#x20; cor da borda: transparente;

&#x20; estilo da borda: sólida;

&#x20; largura-da-borda: 0;

}



.bs-popover-top > .popover-arrow, .bs-popover-auto\[data-popper-placement^=top] > .popover-arrow {

&#x20; inferior: calc(-1 \* (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width));

}

.bs-popover-top > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=top] > .popover-arrow::before, .bs-popover-top > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=top] > .popover-arrow::after {

&#x20; largura-da-borda: var(--bs-popover-arrow-height) calc(var(--bs-popover-arrow-width) \* 0.5) 0;

}

.bs-popover-top > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=top] > .popover-arrow::before {

&#x20; parte inferior: 0;

&#x20; cor-borda-superior: var(--bs-popover-arrow-border);

}

.bs-popover-top > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=top] > .popover-arrow::after {

&#x20; inferior: var(--bs-popover-border-width);

&#x20; cor-borda-superior: var(--bs-popover-bg);

}



/\* rtl:begin:ignore \*/

.bs-popover-end > .popover-arrow, .bs-popover-auto\[data-popper-placement^=right] > .popover-arrow {

&#x20; esquerda: calc(-1 \* (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width));

&#x20; largura: var(--bs-popover-arrow-height);

&#x20; altura: var(--bs-popover-arrow-width);

}

.bs-popover-end > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=right] > .popover-arrow::before, .bs-popover-end > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=right] > .popover-arrow::after {

&#x20; largura-da-borda: calc(var(--bs-popover-arrow-width) \* 0.5) var(--bs-popover-arrow-height) calc(var(--bs-popover-arrow-width) \* 0.5) 0;

}

.bs-popover-end > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=right] > .popover-arrow::before {

&#x20; esquerda: 0;

&#x20; cor-da-borda-direita: var(--bs-popover-arrow-border);

}

.bs-popover-end > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=right] > .popover-arrow::after {

&#x20; esquerda: var(--bs-popover-border-width);

&#x20; cor-da-borda-direita: var(--bs-popover-bg);

}



/\* rtl:end:ignore \*/

.bs-popover-bottom > .popover-arrow, .bs-popover-auto\[data-popper-placement^=bottom] > .popover-arrow {

&#x20; topo: calc(-1 \* (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width));

}

.bs-popover-bottom > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=bottom] > .popover-arrow::before, .bs-popover-bottom > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=bottom] > .popover-arrow::after {

&#x20; largura-da-borda: 0 calc(var(--bs-popover-arrow-width) \* 0.5) var(--bs-popover-arrow-height);

}

.bs-popover-bottom > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=bottom] > .popover-arrow::before {

&#x20; topo: 0;

&#x20; cor-borda-inferior: var(--bs-popover-arrow-border);

}

.bs-popover-bottom > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=bottom] > .popover-arrow::after {

&#x20; topo: var(--bs-popover-border-width);

&#x20; cor-borda-inferior: var(--bs-popover-bg);

}

.bs-popover-bottom .popover-header::before, .bs-popover-auto\[data-popper-placement^=bottom] .popover-header::before {

&#x20; posição: absoluta;

&#x20; topo: 0;

&#x20; esquerda: 50%;

&#x20; exibir: bloco;

&#x20; largura: var(--bs-popover-arrow-width);

&#x20; margem-esquerda: calc(-0.5 \* var(--bs-popover-arrow-width));

&#x20; contente: "";

&#x20; borda inferior: var(--bs-popover-border-width) sólido var(--bs-popover-header-bg);

}



/\* rtl:begin:ignore \*/

.bs-popover-start > .popover-arrow, .bs-popover-auto\[data-popper-placement^=left] > .popover-arrow {

&#x20; direita: calc(-1 \* (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width));

&#x20; largura: var(--bs-popover-arrow-height);

&#x20; altura: var(--bs-popover-arrow-width);

}

.bs-popover-start > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=left] > .popover-arrow::before, .bs-popover-start > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=left] > .popover-arrow::after {

&#x20; largura-da-borda: calc(var(--bs-popover-arrow-width) \* 0.5) 0 calc(var(--bs-popover-arrow-width) \* 0.5) var(--bs-popover-arrow-height);

}

.bs-popover-start > .popover-arrow::before, .bs-popover-auto\[data-popper-placement^=left] > .popover-arrow::before {

&#x20; direita: 0;

&#x20; cor-da-borda-esquerda: var(--bs-popover-arrow-border);

}

.bs-popover-start > .popover-arrow::after, .bs-popover-auto\[data-popper-placement^=left] > .popover-arrow::after {

&#x20; direita: var(--bs-popover-border-width);

&#x20; cor-da-borda-esquerda: var(--bs-popover-bg);

}



/\* rtl:end:ignore \*/

.popover-header {

&#x20; preenchimento: var(--bs-popover-header-padding-y) var(--bs-popover-header-padding-x);

&#x20; margem-inferior: 0;

&#x20; tamanho-da-fonte: var(--bs-popover-header-font-size);

&#x20; cor: var(--bs-popover-header-color);

&#x20; cor de fundo: var(--bs-popover-header-bg);

&#x20; borda-inferior: var(--bs-popover-border-width) sólida var(--bs-popover-border-color);

&#x20; raio-borda-superior-esquerda: var(--bs-popover-inner-border-radius);

&#x20; raio-borda-superior-direita: var(--bs-popover-inner-border-radius);

}

.popover-header:empty {

&#x20; exibir: nenhum;

}



.popover-body {

&#x20; preenchimento: var(--bs-popover-body-padding-y) var(--bs-popover-body-padding-x);

&#x20; cor: var(--bs-popover-body-color);

}



.carrossel {

&#x20; posição: relativa;

}



.carousel.pointer-event {

&#x20; ação por toque: panorâmica;

}



.carousel-inner {

&#x20; posição: relativa;

&#x20; largura: 100%;

&#x20; overflow: oculto;

}

.carousel-inner::after {

&#x20; exibir: bloco;

&#x20; claro: ambos;

&#x20; contente: "";

}



.carousel-item {

&#x20; posição: relativa;

&#x20; exibir: nenhum;

&#x20; flutuar: esquerda;

&#x20; largura: 100%;

&#x20; margem-direita: -100%;

&#x20; -webkit-backface-visibility: oculto;

&#x20; visibilidade da face traseira: oculta;

&#x20; transição: transformar 0,6s com suavização de entrada e saída;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .carousel-item {

&#x20;   transição: nenhuma;

&#x20; }

}



.carousel-item.active,

.carousel-item-next,

.carousel-item-prev {

&#x20; exibir: bloco;

}



.carousel-item-next:não(.carousel-item-start),

.active.carousel-item-end {

&#x20; transformar: traduzirX(100%);

}



.carousel-item-prev:não(.carousel-item-end),

.active.carousel-item-start {

&#x20; transformar: traduzirX(-100%);

}



.carousel-fade .carousel-item {

&#x20; opacidade: 0;

&#x20; propriedade de transição: opacidade;

&#x20; transformar: nenhuma;

}

.carousel-fade .carousel-item.active,

.carousel-fade .carousel-item-next.carousel-item-start,

.carousel-fade .carousel-item-prev.carousel-item-end {

&#x20; Índice z: 1;

&#x20; opacidade: 1;

}

.carousel-fade .active.carousel-item-start,

.carousel-fade .active.carousel-item-end {

&#x20; Índice z: 0;

&#x20; opacidade: 0;

&#x20; transição: opacidade 0s 0,6s;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .carousel-fade .active.carousel-item-start,

&#x20; .carousel-fade .active.carousel-item-end {

&#x20;   transição: nenhuma;

&#x20; }

}



.carousel-control-prev,

.carousel-control-next {

&#x20; posição: absoluta;

&#x20; topo: 0;

&#x20; parte inferior: 0;

&#x20; Índice z: 1;

&#x20; Exibir: flexível;

&#x20; alinhamento-itens: centro;

&#x20; justificar-conteúdo: centralizado;

&#x20; largura: 15%;

&#x20; preenchimento: 0;

&#x20; cor: #fff;

&#x20; alinhamento do texto: centralizado;

&#x20; Contexto: nenhum;

&#x20; borda: 0;

&#x20; opacidade: 0,5;

&#x20; transição: opacidade 0,15s suavização;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .carousel-control-prev,

&#x20; .carousel-control-next {

&#x20;   transição: nenhuma;

&#x20; }

}

.carousel-control-prev:hover, .carousel-control-prev:focus,

.carousel-control-next:hover,

.carousel-control-next:focus {

&#x20; cor: #fff;

&#x20; decoração de texto: nenhuma;

&#x20; esboço: 0;

&#x20; opacidade: 0,9;

}



.carousel-control-prev {

&#x20; esquerda: 0;

}



.carousel-control-next {

&#x20; direita: 0;

}



.carousel-control-prev-icon,

.carousel-control-next-icon {

&#x20; exibição: inline-block;

&#x20; largura: 2rem;

&#x20; altura: 2rem;

&#x20; background-repeat: no-repeat;

&#x20; background-position: 50%;

&#x20; tamanho de fundo: 100% 100%;

}



/\* rtl:opções: {

&#x20; "autoRenomear": verdadeiro,

&#x20; "stringMap":\[ {

&#x20;   "nome" : "anterior-próximo",

&#x20;   "pesquisar" : "anterior",

&#x20;   "substituir" : "próximo"

&#x20; } ]

} \*/

.carousel-control-prev-icon {

&#x20; background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23fff'%3e%3cpath d='M11.354 1.646a.5.5 0 0 1 0 .708L5.707 8l5.647 5.646a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0z'/%3e%3c/svg%3e");

}



.carousel-control-next-icon {

&#x20; background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23fff'%3e%3cpath d='M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");

}



.carousel-indicators {

&#x20; posição: absoluta;

&#x20; direita: 0;

&#x20; parte inferior: 0;

&#x20; esquerda: 0;

&#x20; Índice z: 2;

&#x20; Exibir: flexível;

&#x20; justificar-conteúdo: centralizado;

&#x20; preenchimento: 0;

&#x20; margem-direita: 15%;

&#x20; margem-inferior: 1rem;

&#x20; margem esquerda: 15%;

}

.carousel-indicators \[data-bs-target] {

&#x20; box-sized: content-box;

&#x20; flex: 0 1 auto;

&#x20; largura: 30px;

&#x20; altura: 3px;

&#x20; preenchimento: 0;

&#x20; margem-direita: 3px;

&#x20; margem esquerda: 3px;

&#x20; recuo de texto: -999px;

&#x20; cursor: ponteiro;

&#x20; cor de fundo: #fff;

&#x20; background-clip: padding-box;

&#x20; borda: 0;

&#x20; borda superior: 10px sólida transparente;

&#x20; borda inferior: 10px sólida transparente;

&#x20; opacidade: 0,5;

&#x20; transição: opacidade 0,6s suavização;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .carousel-indicators \[data-bs-target] {

&#x20;   transição: nenhuma;

&#x20; }

}

.carousel-indicators .active {

&#x20; opacidade: 1;

}



.carousel-caption {

&#x20; posição: absoluta;

&#x20; direita: 15%;

&#x20; parte inferior: 1,25rem;

&#x20; esquerda: 15%;

&#x20; acolchoamento superior: 1,25rem;

&#x20; padding-bottom: 1.25rem;

&#x20; cor: #fff;

&#x20; alinhamento do texto: centralizado;

}



.carousel-dark .carousel-control-prev-icon,

.carousel-dark .carousel-control-next-icon {

&#x20; filtro: inverter(1) escala de cinza(100);

}

.carousel-dark .carousel-indicators \[data-bs-target] {

&#x20; cor de fundo: #000;

}

.carousel-dark .carousel-caption {

&#x20; cor: #000;

}



\[data-bs-theme=dark] .carousel .carousel-control-prev-icon,

\[data-bs-theme=dark] .carousel .carousel-control-next-icon, \[data-bs-theme=dark].carousel .carousel-control-prev-icon,

\[data-bs-theme=dark].carousel .carousel-control-next-icon {

&#x20; filtro: inverter(1) escala de cinza(100);

}

\[data-bs-theme=dark] .carousel .carousel-indicators \[data-bs-target], \[data-bs-theme=dark].carousel .carousel-indicators \[data-bs-target] {

&#x20; cor de fundo: #000;

}

\[data-bs-theme=dark] .carousel .carousel-caption, \[data-bs-theme=dark].carousel .carousel-caption {

&#x20; cor: #000;

}



.spinner-crescer,

.borda-do-spinner {

&#x20; exibição: inline-block;

&#x20; largura: var(--bs-spinner-width);

&#x20; altura: var(--bs-spinner-height);

&#x20; alinhamento-vertical: var(--bs-spinner-vertical-align);

&#x20; raio-da-borda: 50%;

&#x20; animação: var(--bs-spinner-animation-speed) linear infinito var(--bs-spinner-animation-name);

}



@keyframes spinner-border {

&#x20; para {

&#x20;   transform: rotate(360deg) /\* rtl:ignore \*/;

&#x20; }

}

.borda-do-spinner {

&#x20; --bs-spinner-width: 2rem;

&#x20; --bs-spinner-height: 2rem;

&#x20; --bs-spinner-vertical-align: -0.125em;

&#x20; --bs-spinner-border-width: 0.25em;

&#x20; --bs-spinner-animation-speed: 0.75s;

&#x20; --bs-spinner-animation-name: spinner-border;

&#x20; borda: var(--bs-spinner-border-width) sólida cor atual;

&#x20; cor da borda direita: transparente;

}



.spinner-border-sm {

&#x20; --bs-spinner-width: 1rem;

&#x20; --bs-spinner-height: 1rem;

&#x20; --bs-spinner-border-width: 0.2em;

}



@keyframes spinner-grow {

&#x20; 0% {

&#x20;   transformar: escala(0);

&#x20; }

&#x20; 50% {

&#x20;   opacidade: 1;

&#x20;   transformar: nenhuma;

&#x20; }

}

.spinner-grow {

&#x20; --bs-spinner-width: 2rem;

&#x20; --bs-spinner-height: 2rem;

&#x20; --bs-spinner-vertical-align: -0.125em;

&#x20; --bs-spinner-animation-speed: 0.75s;

&#x20; --bs-spinner-animation-name: spinner-grow;

&#x20; cor de fundo: cor atual;

&#x20; opacidade: 0;

}



.spinner-grow-sm {

&#x20; --bs-spinner-width: 1rem;

&#x20; --bs-spinner-height: 1rem;

}



@media (prefers-reduced-motion: reduce) {

&#x20; .borda-spinner,

&#x20; .spinner-grow {

&#x20;   --bs-spinner-animation-speed: 1.5s;

&#x20; }

}

.offcanvas, .offcanvas-xxl, .offcanvas-xl, .offcanvas-lg, .offcanvas-md, .offcanvas-sm {

&#x20; --bs-offcanvas-zindex: 1045;

&#x20; --bs-offcanvas-width: 400px;

&#x20; --bs-offcanvas-height: 30vh;

&#x20; --bs-offcanvas-padding-x: 1rem;

&#x20; --bs-offcanvas-padding-y: 1rem;

&#x20; --bs-offcanvas-color: var(--bs-body-color);

&#x20; --bs-offcanvas-bg: var(--bs-body-bg);

&#x20; --bs-offcanvas-border-width: var(--bs-border-width);

&#x20; --bs-offcanvas-border-color: var(--bs-border-color-translucent);

&#x20; --bs-offcanvas-box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);

&#x20; --bs-offcanvas-transition: transformação 0.3s ease-in-out;

&#x20; --bs-offcanvas-title-line-height: 1.5;

}



@media (max-width: 575.98px) {

&#x20; .offcanvas-sm {

&#x20;   posição: fixa;

&#x20;   parte inferior: 0;

&#x20;   índice z: var(--bs-offcanvas-zindex);

&#x20;   Exibir: flexível;

&#x20;   flex-direction: coluna;

&#x20;   largura máxima: 100%;

&#x20;   cor: var(--bs-offcanvas-color);

&#x20;   visibilidade: oculta;

&#x20;   cor de fundo: var(--bs-offcanvas-bg);

&#x20;   background-clip: padding-box;

&#x20;   esboço: 0;

&#x20;   transição: var(--bs-offcanvas-transition);

&#x20; }

}

@media (max-width: 575.98px) and (prefers-reduced-motion: reduce) {

&#x20; .offcanvas-sm {

&#x20;   transição: nenhuma;

&#x20; }

}

@media (max-width: 575.98px) {

&#x20; .offcanvas-sm.offcanvas-start {

&#x20;   topo: 0;

&#x20;   esquerda: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-direita: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(-100%);

&#x20; }

&#x20; .offcanvas-sm.offcanvas-end {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-esquerda: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(100%);

&#x20; }

&#x20; .offcanvas-sm.offcanvas-top {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-inferior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(-100%);

&#x20; }

&#x20; .offcanvas-sm.offcanvas-bottom {

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-superior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(100%);

&#x20; }

&#x20; .offcanvas-sm.showing, .offcanvas-sm.show:not(.hiding) {

&#x20;   transformar: nenhuma;

&#x20; }

&#x20; .offcanvas-sm.showing, .offcanvas-sm.hiding, .offcanvas-sm.show {

&#x20;   visibilidade: visível;

&#x20; }

}

@media (min-width: 576px) {

&#x20; .offcanvas-sm {

&#x20;   --bs-offcanvas-height: auto;

&#x20;   --bs-offcanvas-border-width: 0;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

&#x20; .offcanvas-sm .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .offcanvas-sm .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

}



@media (max-width: 767.98px) {

&#x20; .offcanvas-md {

&#x20;   posição: fixa;

&#x20;   parte inferior: 0;

&#x20;   índice z: var(--bs-offcanvas-zindex);

&#x20;   Exibir: flexível;

&#x20;   flex-direction: coluna;

&#x20;   largura máxima: 100%;

&#x20;   cor: var(--bs-offcanvas-color);

&#x20;   visibilidade: oculta;

&#x20;   cor de fundo: var(--bs-offcanvas-bg);

&#x20;   background-clip: padding-box;

&#x20;   esboço: 0;

&#x20;   transição: var(--bs-offcanvas-transition);

&#x20; }

}

@media (max-width: 767.98px) and (prefers-reduced-motion: reduce) {

&#x20; .offcanvas-md {

&#x20;   transição: nenhuma;

&#x20; }

}

@media (max-width: 767.98px) {

&#x20; .offcanvas-md.offcanvas-start {

&#x20;   topo: 0;

&#x20;   esquerda: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-direita: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(-100%);

&#x20; }

&#x20; .offcanvas-md.offcanvas-end {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-esquerda: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(100%);

&#x20; }

&#x20; .offcanvas-md.offcanvas-top {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-inferior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(-100%);

&#x20; }

&#x20; .offcanvas-md.offcanvas-bottom {

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-superior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(100%);

&#x20; }

&#x20; .offcanvas-md.showing, .offcanvas-md.show:not(.hiding) {

&#x20;   transformar: nenhuma;

&#x20; }

&#x20; .offcanvas-md.showing, .offcanvas-md.hiding, .offcanvas-md.show {

&#x20;   visibilidade: visível;

&#x20; }

}

@media (min-width: 768px) {

&#x20; .offcanvas-md {

&#x20;   --bs-offcanvas-height: auto;

&#x20;   --bs-offcanvas-border-width: 0;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

&#x20; .offcanvas-md .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .offcanvas-md .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

}



@media (max-width: 991.98px) {

&#x20; .offcanvas-lg {

&#x20;   posição: fixa;

&#x20;   parte inferior: 0;

&#x20;   índice z: var(--bs-offcanvas-zindex);

&#x20;   Exibir: flexível;

&#x20;   flex-direction: coluna;

&#x20;   largura máxima: 100%;

&#x20;   cor: var(--bs-offcanvas-color);

&#x20;   visibilidade: oculta;

&#x20;   cor de fundo: var(--bs-offcanvas-bg);

&#x20;   background-clip: padding-box;

&#x20;   esboço: 0;

&#x20;   transição: var(--bs-offcanvas-transition);

&#x20; }

}

@media (max-width: 991.98px) and (prefers-reduced-motion: reduce) {

&#x20; .offcanvas-lg {

&#x20;   transição: nenhuma;

&#x20; }

}

@media (max-width: 991.98px) {

&#x20; .offcanvas-lg.offcanvas-start {

&#x20;   topo: 0;

&#x20;   esquerda: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-direita: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(-100%);

&#x20; }

&#x20; .offcanvas-lg.offcanvas-end {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-esquerda: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(100%);

&#x20; }

&#x20; .offcanvas-lg.offcanvas-top {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-inferior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(-100%);

&#x20; }

&#x20; .offcanvas-lg.offcanvas-bottom {

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-superior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(100%);

&#x20; }

&#x20; .offcanvas-lg.showing, .offcanvas-lg.show:not(.hiding) {

&#x20;   transformar: nenhuma;

&#x20; }

&#x20; .offcanvas-lg.showing, .offcanvas-lg.hiding, .offcanvas-lg.show {

&#x20;   visibilidade: visível;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .offcanvas-lg {

&#x20;   --bs-offcanvas-height: auto;

&#x20;   --bs-offcanvas-border-width: 0;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

&#x20; .offcanvas-lg .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .offcanvas-lg .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

}



@media (max-width: 1199.98px) {

&#x20; .offcanvas-xl {

&#x20;   posição: fixa;

&#x20;   parte inferior: 0;

&#x20;   índice z: var(--bs-offcanvas-zindex);

&#x20;   Exibir: flexível;

&#x20;   flex-direction: coluna;

&#x20;   largura máxima: 100%;

&#x20;   cor: var(--bs-offcanvas-color);

&#x20;   visibilidade: oculta;

&#x20;   cor de fundo: var(--bs-offcanvas-bg);

&#x20;   background-clip: padding-box;

&#x20;   esboço: 0;

&#x20;   transição: var(--bs-offcanvas-transition);

&#x20; }

}

@media (max-width: 1199.98px) and (prefers-reduced-motion: reduce) {

&#x20; .offcanvas-xl {

&#x20;   transição: nenhuma;

&#x20; }

}

@media (max-width: 1199.98px) {

&#x20; .offcanvas-xl.offcanvas-start {

&#x20;   topo: 0;

&#x20;   esquerda: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-direita: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(-100%);

&#x20; }

&#x20; .offcanvas-xl.offcanvas-end {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-esquerda: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(100%);

&#x20; }

&#x20; .offcanvas-xl.offcanvas-top {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-inferior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(-100%);

&#x20; }

&#x20; .offcanvas-xl.offcanvas-bottom {

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-superior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(100%);

&#x20; }

&#x20; .offcanvas-xl.showing, .offcanvas-xl.show:not(.hiding) {

&#x20;   transformar: nenhuma;

&#x20; }

&#x20; .offcanvas-xl.showing, .offcanvas-xl.hiding, .offcanvas-xl.show {

&#x20;   visibilidade: visível;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .offcanvas-xl {

&#x20;   --bs-offcanvas-height: auto;

&#x20;   --bs-offcanvas-border-width: 0;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

&#x20; .offcanvas-xl .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .offcanvas-xl .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

}



@media (max-width: 1399.98px) {

&#x20; .offcanvas-xxl {

&#x20;   posição: fixa;

&#x20;   parte inferior: 0;

&#x20;   índice z: var(--bs-offcanvas-zindex);

&#x20;   Exibir: flexível;

&#x20;   flex-direction: coluna;

&#x20;   largura máxima: 100%;

&#x20;   cor: var(--bs-offcanvas-color);

&#x20;   visibilidade: oculta;

&#x20;   cor de fundo: var(--bs-offcanvas-bg);

&#x20;   background-clip: padding-box;

&#x20;   esboço: 0;

&#x20;   transição: var(--bs-offcanvas-transition);

&#x20; }

}

@media (max-width: 1399.98px) and (prefers-reduced-motion: reduce) {

&#x20; .offcanvas-xxl {

&#x20;   transição: nenhuma;

&#x20; }

}

@media (max-width: 1399.98px) {

&#x20; .offcanvas-xxl.offcanvas-start {

&#x20;   topo: 0;

&#x20;   esquerda: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-direita: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(-100%);

&#x20; }

&#x20; .offcanvas-xxl.offcanvas-end {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   largura: var(--bs-offcanvas-width);

&#x20;   borda-esquerda: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirX(100%);

&#x20; }

&#x20; .offcanvas-xxl.offcanvas-top {

&#x20;   topo: 0;

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-inferior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(-100%);

&#x20; }

&#x20; .offcanvas-xxl.offcanvas-bottom {

&#x20;   direita: 0;

&#x20;   esquerda: 0;

&#x20;   altura: var(--bs-offcanvas-height);

&#x20;   altura máxima: 100%;

&#x20;   borda-superior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20;   transformar: traduzirY(100%);

&#x20; }

&#x20; .offcanvas-xxl.showing, .offcanvas-xxl.show:not(.hiding) {

&#x20;   transformar: nenhuma;

&#x20; }

&#x20; .offcanvas-xxl.showing, .offcanvas-xxl.hiding, .offcanvas-xxl.show {

&#x20;   visibilidade: visível;

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .offcanvas-xxl {

&#x20;   --bs-offcanvas-height: auto;

&#x20;   --bs-offcanvas-border-width: 0;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

&#x20; .offcanvas-xxl .offcanvas-header {

&#x20;   exibir: nenhum;

&#x20; }

&#x20; .offcanvas-xxl .offcanvas-body {

&#x20;   Exibir: flexível;

&#x20;   flex-grow: 0;

&#x20;   preenchimento: 0;

&#x20;   overflow-y: visível;

&#x20;   cor de fundo: transparente !importante;

&#x20; }

}



.offcanvas {

&#x20; posição: fixa;

&#x20; parte inferior: 0;

&#x20; índice z: var(--bs-offcanvas-zindex);

&#x20; Exibir: flexível;

&#x20; flex-direction: coluna;

&#x20; largura máxima: 100%;

&#x20; cor: var(--bs-offcanvas-color);

&#x20; visibilidade: oculta;

&#x20; cor de fundo: var(--bs-offcanvas-bg);

&#x20; background-clip: padding-box;

&#x20; esboço: 0;

&#x20; transição: var(--bs-offcanvas-transition);

}

@media (prefers-reduced-motion: reduce) {

&#x20; .offcanvas {

&#x20;   transição: nenhuma;

&#x20; }

}

.offcanvas.offcanvas-start {

&#x20; topo: 0;

&#x20; esquerda: 0;

&#x20; largura: var(--bs-offcanvas-width);

&#x20; borda-direita: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20; transformar: traduzirX(-100%);

}

.offcanvas.offcanvas-end {

&#x20; topo: 0;

&#x20; direita: 0;

&#x20; largura: var(--bs-offcanvas-width);

&#x20; borda-esquerda: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20; transformar: traduzirX(100%);

}

.offcanvas.offcanvas-top {

&#x20; topo: 0;

&#x20; direita: 0;

&#x20; esquerda: 0;

&#x20; altura: var(--bs-offcanvas-height);

&#x20; altura máxima: 100%;

&#x20; borda-inferior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20; transformar: traduzirY(-100%);

}

.offcanvas.offcanvas-bottom {

&#x20; direita: 0;

&#x20; esquerda: 0;

&#x20; altura: var(--bs-offcanvas-height);

&#x20; altura máxima: 100%;

&#x20; borda-superior: var(--bs-offcanvas-border-width) sólida var(--bs-offcanvas-border-color);

&#x20; transformar: traduzirY(100%);

}

.offcanvas.showing, .offcanvas.show:not(.hiding) {

&#x20; transformar: nenhuma;

}

.offcanvas.showing, .offcanvas.hiding, .offcanvas.show {

&#x20; visibilidade: visível;

}



.offcanvas-backdrop {

&#x20; posição: fixa;

&#x20; topo: 0;

&#x20; esquerda: 0;

&#x20; Índice z: 1040;

&#x20; largura: 100vw;

&#x20; altura: 100vh;

&#x20; cor de fundo: #000;

}

.offcanvas-backdrop.fade {

&#x20; opacidade: 0;

}

.offcanvas-backdrop.show {

&#x20; opacidade: 0,5;

}



.offcanvas-header {

&#x20; Exibir: flexível;

&#x20; alinhamento-itens: centro;

&#x20; justify-content: espaço-entre;

&#x20; preenchimento: var(--bs-offcanvas-padding-y) var(--bs-offcanvas-padding-x);

}

.offcanvas-header .btn-close {

&#x20; preenchimento: calc(var(--bs-offcanvas-padding-y) \* 0.5) calc(var(--bs-offcanvas-padding-x) \* 0.5);

&#x20; margem-superior: calc(-0.5 \* var(--bs-offcanvas-padding-y));

&#x20; margem-direita: calc(-0.5 \* var(--bs-offcanvas-padding-x));

&#x20; margem inferior: calc(-0,5 \* var(--bs-offcanvas-padding-y));

}



.offcanvas-title {

&#x20; margem-inferior: 0;

&#x20; altura-da-linha: var(--bs-offcanvas-title-line-height);

}



.offcanvas-body {

&#x20; flex-grow: 1;

&#x20; preenchimento: var(--bs-offcanvas-padding-y) var(--bs-offcanvas-padding-x);

&#x20; overflow-y: automático;

}



.placeholder {

&#x20; exibição: inline-block;

&#x20; altura mínima: 1em;

&#x20; alinhamento vertical: meio;

&#x20; cursor: aguarde;

&#x20; cor de fundo: cor atual;

&#x20; opacidade: 0,5;

}

.placeholder.btn::before {

&#x20; exibição: inline-block;

&#x20; contente: "";

}



.placeholder-xs {

&#x20; altura mínima: 0,6em;

}



.placeholder-sm {

&#x20; altura mínima: 0,8em;

}



.placeholder-lg {

&#x20; altura mínima: 1,2em;

}



.placeholder-glow .placeholder {

&#x20; animação: brilho de espaço reservado 2s entrada e saída suaves infinitas;

}



@keyframes placeholder-glow {

&#x20; 50% {

&#x20;   opacidade: 0,2;

&#x20; }

}

.placeholder-wave {

&#x20; -webkit-mask-image: linear-gradient(130deg, #000 55%, rgba(0, 0, 0, 0.8) 75%, #000 95%);

&#x20; máscara-imagem: gradiente-linear(130deg, #000 55%, rgba(0, 0, 0, 0.8) 75%, #000 95%);

&#x20; -webkit-mask-size: 200% 100%;

&#x20; Tamanho da máscara: 200% 100%;

&#x20; animação: placeholder-wave 2s linear infinito;

}



@keyframes placeholder-wave {

&#x20; 100% {

&#x20;   -webkit-mask-position: -200% 0%;

&#x20;   posição da máscara: -200% 0%;

&#x20; }

}

.clearfix::after {

&#x20; exibir: bloco;

&#x20; claro: ambos;

&#x20; contente: "";

}



.text-bg-primary {

&#x20; cor: #fff !importante;

&#x20; background-color: RGBA(13, 110, 253, var(--bs-bg-opacity, 1)) !important;

}



.text-bg-secondary {

&#x20; cor: #fff !importante;

&#x20; background-color: RGBA(108, 117, 125, var(--bs-bg-opacity, 1)) !important;

}



.text-bg-success {

&#x20; cor: #fff !importante;

&#x20; background-color: RGBA(25, 135, 84, var(--bs-bg-opacity, 1)) !important;

}



.text-bg-info {

&#x20; cor: #000 !importante;

&#x20; background-color: RGBA(13, 202, 240, var(--bs-bg-opacity, 1)) !important;

}



.text-bg-warning {

&#x20; cor: #000 !importante;

&#x20; background-color: RGBA(255, 193, 7, var(--bs-bg-opacity, 1)) !important;

}



.text-bg-danger {

&#x20; cor: #fff !importante;

&#x20; background-color: RGBA(220, 53, 69, var(--bs-bg-opacity, 1)) !important;

}



.text-bg-light {

&#x20; cor: #000 !importante;

&#x20; background-color: RGBA(248, 249, 250, var(--bs-bg-opacity, 1)) !important;

}



.text-bg-dark {

&#x20; cor: #fff !importante;

&#x20; background-color: RGBA(33, 37, 41, var(--bs-bg-opacity, 1)) !important;

}



.link-primary {

&#x20; cor: RGBA(var(--bs-primary-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-primary-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-primary-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-primary:hover, .link-primary:focus {

&#x20; cor: RGBA(10, 88, 202, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(10, 88, 202, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(10, 88, 202, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-secondary {

&#x20; cor: RGBA(var(--bs-secondary-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-secondary-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-secondary-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-secondary:hover, .link-secondary:focus {

&#x20; cor: RGBA(86, 94, 100, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(86, 94, 100, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(86, 94, 100, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-success {

&#x20; cor: RGBA(var(--bs-success-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-success-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-success-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-success:hover, .link-success:focus {

&#x20; cor: RGBA(20, 108, 67, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(20, 108, 67, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(20, 108, 67, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-info {

&#x20; cor: RGBA(var(--bs-info-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-info-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-info-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-info:hover, .link-info:focus {

&#x20; cor: RGBA(61, 213, 243, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(61, 213, 243, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(61, 213, 243, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-warning {

&#x20; cor: RGBA(var(--bs-warning-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-warning-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-warning-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-warning:hover, .link-warning:focus {

&#x20; cor: RGBA(255, 205, 57, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(255, 205, 57, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(255, 205, 57, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-danger {

&#x20; cor: RGBA(var(--bs-danger-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-danger-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-danger-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-danger:hover, .link-danger:focus {

&#x20; cor: RGBA(176, 42, 55, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(176, 42, 55, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(176, 42, 55, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-light {

&#x20; cor: RGBA(var(--bs-light-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-light-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-light-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-light:hover, .link-light:focus {

&#x20; cor: RGBA(249, 250, 251, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(249, 250, 251, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(249, 250, 251, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-dark {

&#x20; cor: RGBA(var(--bs-dark-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-dark-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-dark-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-dark:hover, .link-dark:focus {

&#x20; cor: RGBA(26, 30, 33, var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(26, 30, 33, var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(26, 30, 33, var(--bs-link-underline-opacity, 1)) !importante;

}



.link-body-emphasis {

&#x20; cor: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-opacity, 1)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 1)) !importante;

}

.link-body-emphasis:hover, .link-body-emphasis:focus {

&#x20; cor: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-opacity, 0.75)) !importante;

&#x20; -webkit-text-decoration-color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 0.75)) !important;

&#x20; cor-decoração-texto: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 0.75)) !importante;

}



.focus-ring:focus {

&#x20; esboço: 0;

&#x20; box-shadow: var(--bs-focus-ring-x, 0) var(--bs-focus-ring-y, 0) var(--bs-focus-ring-blur, 0) var(--bs-focus-ring-width) var(--bs-focus-ring-color);

}



.icon-link {

&#x20; exibição: inline-flex;

&#x20; intervalo: 0,375rem;

&#x20; alinhamento-itens: centro;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-link-color-rgb), var(--bs-link-opacity, 0.5));

&#x20; cor-decoração-texto: rgba(var(--bs-link-color-rgb), var(--bs-link-opacity, 0.5));

&#x20; deslocamento-sublinhado-texto: 0,25em;

&#x20; -webkit-backface-visibility: oculto;

&#x20; visibilidade da face traseira: oculta;

}

.icon-link > .bi ​​{

&#x20; flex-shrink: 0;

&#x20; largura: 1em;

&#x20; altura: 1em;

&#x20; preenchimento: coratual;

&#x20; transição: transformação de entrada e saída suave de 0,2s;

}

@media (prefers-reduced-motion: reduce) {

&#x20; .icon-link > .bi ​​{

&#x20;   transição: nenhuma;

&#x20; }

}



.icon-link-hover:hover > .bi, .icon-link-hover:focus-visible > .bi ​​{

&#x20; transformação: var(--bs-icon-link-transform, translate3d(0.25em, 0, 0));

}



.razão {

&#x20; posição: relativa;

&#x20; largura: 100%;

}

.ratio::before {

&#x20; exibir: bloco;

&#x20; padding-top: var(--bs-aspect-ratio);

&#x20; contente: "";

}

.razão > \* {

&#x20; posição: absoluta;

&#x20; topo: 0;

&#x20; esquerda: 0;

&#x20; largura: 100%;

&#x20; altura: 100%;

}



.razão-1x1 {

&#x20; --bs-aspect-ratio: 100%;

}



.razão-4x3 {

&#x20; --bs-aspect-ratio: 75%;

}



.ratio-16x9 {

&#x20; --bs-aspect-ratio: 56,25%;

}



.razão-21x9 {

&#x20; --bs-aspect-ratio: 42.8571428571%;

}



.fixo-superior {

&#x20; posição: fixa;

&#x20; topo: 0;

&#x20; direita: 0;

&#x20; esquerda: 0;

&#x20; Índice z: 1030;

}



.fixed-bottom {

&#x20; posição: fixa;

&#x20; direita: 0;

&#x20; parte inferior: 0;

&#x20; esquerda: 0;

&#x20; Índice z: 1030;

}



.sticky-top {

&#x20; posição: -webkit-sticky;

&#x20; posição: pegajosa;

&#x20; topo: 0;

&#x20; Índice z: 1020;

}



.sticky-bottom {

&#x20; posição: -webkit-sticky;

&#x20; posição: pegajosa;

&#x20; parte inferior: 0;

&#x20; Índice z: 1020;

}



@media (min-width: 576px) {

&#x20; .sticky-sm-top {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   topo: 0;

&#x20;   Índice z: 1020;

&#x20; }

&#x20; .sticky-sm-bottom {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   parte inferior: 0;

&#x20;   Índice z: 1020;

&#x20; }

}

@media (min-width: 768px) {

&#x20; .sticky-md-top {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   topo: 0;

&#x20;   Índice z: 1020;

&#x20; }

&#x20; .sticky-md-bottom {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   parte inferior: 0;

&#x20;   Índice z: 1020;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .sticky-lg-top {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   topo: 0;

&#x20;   Índice z: 1020;

&#x20; }

&#x20; .sticky-lg-bottom {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   parte inferior: 0;

&#x20;   Índice z: 1020;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .sticky-xl-top {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   topo: 0;

&#x20;   Índice z: 1020;

&#x20; }

&#x20; .sticky-xl-bottom {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   parte inferior: 0;

&#x20;   Índice z: 1020;

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .sticky-xxl-top {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   topo: 0;

&#x20;   Índice z: 1020;

&#x20; }

&#x20; .sticky-xxl-bottom {

&#x20;   posição: -webkit-sticky;

&#x20;   posição: pegajosa;

&#x20;   parte inferior: 0;

&#x20;   Índice z: 1020;

&#x20; }

}

.hstack {

&#x20; Exibir: flexível;

&#x20; flex-direction: linha;

&#x20; alinhamento-itens: centro;

&#x20; alinhar-si: esticar;

}



.vstack {

&#x20; Exibir: flexível;

&#x20; flex: 1 1 auto;

&#x20; flex-direction: coluna;

&#x20; alinhar-si: esticar;

}



.visualmente-oculto,

.visually-hidden-focusable:not(:focus):not(:focus-within) {

&#x20; largura: 1px !importante;

&#x20; altura: 1px !importante;

&#x20; preenchimento: 0 !importante;

&#x20; margem: -1px !importante;

&#x20; overflow: oculto !importante;

&#x20; recorte: rect(0, 0, 0, 0) !importante;

&#x20; white-space: nowrap !important;

&#x20; borda: 0 !importante;

}

.visualmente-oculto:não(legenda),

.visually-hidden-focusable:not(:focus):not(:focus-within):not(caption) {

&#x20; posição: absoluta !importante;

}



.stretched-link::after {

&#x20; posição: absoluta;

&#x20; topo: 0;

&#x20; direita: 0;

&#x20; parte inferior: 0;

&#x20; esquerda: 0;

&#x20; Índice z: 1;

&#x20; contente: "";

}



.text-truncate {

&#x20; overflow: oculto;

&#x20; estouro de texto: reticências;

&#x20; espaço em branco: nowrap;

}



.vr {

&#x20; exibição: inline-block;

&#x20; alinhar-si: esticar;

&#x20; largura: 1px;

&#x20; altura mínima: 1em;

&#x20; cor de fundo: cor atual;

&#x20; opacidade: 0,25;

}



.align-baseline {

&#x20; alinhamento vertical: linha de base !importante;

}



.align-top {

&#x20; alinhamento vertical: superior !importante;

}



.align-middle {

&#x20; alinhamento vertical: meio !importante;

}



.align-bottom {

&#x20; alinhamento vertical: inferior !importante;

}



.align-text-bottom {

&#x20; alinhamento vertical: texto-inferior !importante;

}



.align-text-top {

&#x20; alinhamento-vertical: texto-acima !importante;

}



.float-start {

&#x20; flutuar: esquerda !importante;

}



.float-end {

&#x20; flutuar: direita !importante;

}



.float-none {

&#x20; flutuar: nenhum !importante;

}



.object-fit-contain {

&#x20; -o-object-fit: contém !importante;

&#x20; object-fit: conter !important;

}



.object-fit-cover {

&#x20; -o-object-fit: cobrir !importante;

&#x20; object-fit: cobrir !importante;

}



.object-fit-fill {

&#x20; -o-object-fit: preencher !importante;

&#x20; object-fit: preencher !important;

}



.object-fit-scale {

&#x20; -o-object-fit: reduzir a escala !importante;

&#x20; object-fit: reduzir escala !important;

}



.object-fit-none {

&#x20; -o-object-fit: nenhum !importante;

&#x20; object-fit: none !important;

}



.opacidade-0 {

&#x20; opacidade: 0 !importante;

}



.opacidade-25 {

&#x20; opacidade: 0,25 !importante;

}



.opacidade-50 {

&#x20; opacidade: 0,5 !importante;

}



.opacidade-75 {

&#x20; opacidade: 0,75 !importante;

}



.opacidade-100 {

&#x20; opacidade: 1 !importante;

}



.overflow-auto {

&#x20; overflow: auto !important;

}



.overflow-hidden {

&#x20; overflow: oculto !importante;

}



.overflow-visible {

&#x20; overflow: visível !importante;

}



.overflow-scroll {

&#x20; overflow: scroll !important;

}



.overflow-x-auto {

&#x20; overflow-x: auto !important;

}



.overflow-x-hidden {

&#x20; overflow-x: oculto !importante;

}



.overflow-x-visible {

&#x20; overflow-x: visível !importante;

}



.overflow-x-scroll {

&#x20; overflow-x: rolagem !importante;

}



.overflow-y-auto {

&#x20; overflow-y: auto !important;

}



.overflow-y-hidden {

&#x20; overflow-y: oculto !importante;

}



.overflow-y-visible {

&#x20; overflow-y: visível !importante;

}



.overflow-y-scroll {

&#x20; overflow-y: rolagem !importante;

}



.d-inline {

&#x20; exibir: embutido !importante;

}



.d-inline-block {

&#x20; exibir: inline-block !important;

}



.d-block {

&#x20; exibir: bloco !importante;

}



.d-grid {

&#x20; exibir: grade !importante;

}



.d-inline-grid {

&#x20; exibição: grade em linha !importante;

}



.d-table {

&#x20; exibir: tabela !importante;

}



.d-table-row {

&#x20; exibir: linha-da-tabela !importante;

}



.d-table-cell {

&#x20; exibir: célula-da-tabela !importante;

}



.d-flex {

&#x20; exibir: flex !importante;

}



.d-inline-flex {

&#x20; exibir: inline-flex !important;

}



.d-nenhum {

&#x20; exibir: nenhum !importante;

}



.sombra {

&#x20; box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15) !important;

}



.shadow-sm {

&#x20; box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075) !important;

}



.shadow-lg {

&#x20; box-shadow: 0 1rem 3rem rgba(0, 0, 0, 0.175) !important;

}



.shadow-none {

&#x20; box-shadow: none !important;

}



.focus-ring-primary {

&#x20; --bs-focus-ring-color: rgba(var(--bs-primary-rgb), var(--bs-focus-ring-opacity));

}



.focus-ring-secondary {

&#x20; --bs-focus-ring-color: rgba(var(--bs-secondary-rgb), var(--bs-focus-ring-opacity));

}



.focus-ring-success {

&#x20; --bs-focus-ring-color: rgba(var(--bs-success-rgb), var(--bs-focus-ring-opacity));

}



.focus-ring-info {

&#x20; --bs-focus-ring-color: rgba(var(--bs-info-rgb), var(--bs-focus-ring-opacity));

}



.focus-ring-warning {

&#x20; --bs-focus-ring-color: rgba(var(--bs-warning-rgb), var(--bs-focus-ring-opacity));

}



.focus-ring-danger {

&#x20; --bs-focus-ring-color: rgba(var(--bs-danger-rgb), var(--bs-focus-ring-opacity));

}



.focus-ring-light {

&#x20; --bs-focus-ring-color: rgba(var(--bs-light-rgb), var(--bs-focus-ring-opacity));

}



.focus-ring-dark {

&#x20; --bs-focus-ring-color: rgba(var(--bs-dark-rgb), var(--bs-focus-ring-opacity));

}



.position-static {

&#x20; posição: estática !importante;

}



.posição-relativa {

&#x20; posição: relativa !importante;

}



.posição-absoluta {

&#x20; posição: absoluta !importante;

}



.posição-fixa {

&#x20; posição: fixa !importante;

}



.position-sticky {

&#x20; posição: -webkit-sticky !importante;

&#x20; posição: fixa !importante;

}



.top-0 {

&#x20; topo: 0 !importante;

}



.top-50 {

&#x20; topo: 50% !importante;

}



.top-100 {

&#x20; topo: 100% !importante;

}



.bottom-0 {

&#x20; parte inferior: 0 !importante;

}



.bottom-50 {

&#x20; parte inferior: 50% !importante;

}



.bottom-100 {

&#x20; parte inferior: 100% !importante;

}



.start-0 {

&#x20; esquerda: 0 !importante;

}



.start-50 {

&#x20; esquerda: 50% !importante;

}



.start-100 {

&#x20; esquerda: 100% !importante;

}



.fim-0 {

&#x20; direita: 0 !importante;

}



.fim-50 {

&#x20; direita: 50% !importante;

}



.fim-100 {

&#x20; direita: 100% !importante;

}



.translate-middle {

&#x20; transformar: traduzir(-50%, -50%) !importante;

}



.translate-middle-x {

&#x20; transformar: traduzirX(-50%) !importante;

}



.translate-middle-y {

&#x20; transformar: traduzirY(-50%) !importante;

}



.fronteira {

&#x20; borda: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !importante;

}



.border-0 {

&#x20; borda: 0 !importante;

}



.border-top {

&#x20; borda superior: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !importante;

}



.border-top-0 {

&#x20; borda-superior: 0 !importante;

}



.border-end {

&#x20; borda direita: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !importante;

}



.border-end-0 {

&#x20; borda-direita: 0 !importante;

}



.border-bottom {

&#x20; borda inferior: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !importante;

}



.border-bottom-0 {

&#x20; borda-inferior: 0 !importante;

}



.border-start {

&#x20; borda esquerda: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !importante;

}



.border-start-0 {

&#x20; borda-esquerda: 0 !importante;

}



.border-primary {

&#x20; --bs-border-opacity: 1;

&#x20; cor da borda: rgba(var(--bs-primary-rgb), var(--bs-border-opacity)) !importante;

}



.border-secondary {

&#x20; --bs-border-opacity: 1;

&#x20; border-color: rgba(var(--bs-secondary-rgb), var(--bs-border-opacity)) !important;

}



.border-success {

&#x20; --bs-border-opacity: 1;

&#x20; border-color: rgba(var(--bs-success-rgb), var(--bs-border-opacity)) !important;

}



.border-info {

&#x20; --bs-border-opacity: 1;

&#x20; cor da borda: rgba(var(--bs-info-rgb), var(--bs-border-opacity)) !importante;

}



.border-warning {

&#x20; --bs-border-opacity: 1;

&#x20; cor da borda: rgba(var(--bs-warning-rgb), var(--bs-border-opacity)) !importante;

}



.border-danger {

&#x20; --bs-border-opacity: 1;

&#x20; cor da borda: rgba(var(--bs-danger-rgb), var(--bs-border-opacity)) !importante;

}



.border-light {

&#x20; --bs-border-opacity: 1;

&#x20; border-color: rgba(var(--bs-light-rgb), var(--bs-border-opacity)) !important;

}



.border-dark {

&#x20; --bs-border-opacity: 1;

&#x20; cor da borda: rgba(var(--bs-dark-rgb), var(--bs-border-opacity)) !importante;

}



.border-black {

&#x20; --bs-border-opacity: 1;

&#x20; border-color: rgba(var(--bs-black-rgb), var(--bs-border-opacity)) !important;

}



.border-white {

&#x20; --bs-border-opacity: 1;

&#x20; border-color: rgba(var(--bs-white-rgb), var(--bs-border-opacity)) !important;

}



.border-primary-subtle {

&#x20; cor-da-borda: var(--bs-primary-border-subtle) !importante;

}



.border-secondary-subtle {

&#x20;cor-da-borda: var(--bs-secondary-border-subtle) !importante;

}



.border-success-subtle {

&#x20; cor-da-borda: var(--bs-success-border-subtle) !importante;

}



.border-info-subtle {

&#x20; cor-da-borda: var(--bs-info-border-subtle) !importante;

}



.border-warning-subtle {

&#x20; cor-da-borda: var(--bs-warning-border-subtle) !importante;

}



.border-danger-subtle {

&#x20; cor-da-borda: var(--bs-danger-border-subtle) !importante;

}



.border-light-subtle {

&#x20; cor-da-borda: var(--bs-light-border-subtle) !importante;

}



.border-dark-subtle {

&#x20; cor-da-borda: var(--bs-dark-border-subtle) !importante;

}



.border-1 {

&#x20; largura-da-borda: 1px !importante;

}



.border-2 {

&#x20; largura-da-borda: 2px !importante;

}



.border-3 {

&#x20; largura-da-borda: 3px !importante;

}



.border-4 {

&#x20; largura-da-borda: 4px !importante;

}



.border-5 {

&#x20; largura-da-borda: 5px !importante;

}



.border-opacity-10 {

&#x20; --bs-border-opacity: 0.1;

}



.border-opacity-25 {

&#x20; --bs-border-opacity: 0.25;

}



.border-opacity-50 {

&#x20; --bs-border-opacity: 0.5;

}



.border-opacity-75 {

&#x20; --bs-border-opacity: 0.75;

}



.border-opacity-100 {

&#x20; --bs-border-opacity: 1;

}



.w-25 {

&#x20; largura: 25% !importante;

}



.w-50 {

&#x20; largura: 50% !importante;

}



.w-75 {

&#x20; largura: 75% !importante;

}



.w-100 {

&#x20; largura: 100% !importante;

}



.w-auto {

&#x20; largura: automática !importante;

}



.mw-100 {

&#x20; largura-máxima: 100% !importante;

}



.vw-100 {

&#x20; largura: 100vw !importante;

}



.min-vw-100 {

&#x20; largura mínima: 100vw !importante;

}



.h-25 {

&#x20; altura: 25% !importante;

}



.h-50 {

&#x20; altura: 50% !importante;

}



.h-75 {

&#x20; altura: 75% !importante;

}



.h-100 {

&#x20; altura: 100% !importante;

}



.h-auto {

&#x20; altura: automática !importante;

}



.mh-100 {

&#x20; altura máxima: 100% !importante;

}



.vh-100 {

&#x20; altura: 100vh !importante;

}



.min-vh-100 {

&#x20; altura mínima: 100vh !importante;

}



.flex-fill {

&#x20; flex: 1 1 auto !importante;

}



.flex-row {

&#x20; flex-direction: linha !importante;

}



.flex-column {

&#x20; flex-direction: coluna !importante;

}



.flex-row-reverse {

&#x20; flex-direction: row-reverse !important;

}



.flex-column-reverse {

&#x20; flex-direction: column-reverse !important;

}



.flex-grow-0 {

&#x20; flex-grow: 0 !importante;

}



.flex-grow-1 {

&#x20; flex-grow: 1 !importante;

}



.flex-shrink-0 {

&#x20; flex-shrink: 0 !importante;

}



.flex-shrink-1 {

&#x20; flex-shrink: 1 !importante;

}



.flex-wrap {

&#x20; flex-wrap: envolver !importante;

}



.flex-nowrap {

&#x20; flex-wrap: nowrap !important;

}



.flex-wrap-reverse {

&#x20; flex-wrap: wrap-reverse !important;

}



.justify-content-start {

&#x20; justify-content: flex-start !important;

}



.justify-content-end {

&#x20; justify-content: flex-end !important;

}



.justify-content-center {

&#x20; justify-content: center !important;

}



.justify-content-between {

&#x20; justify-content: espaço-entre !important;

}



.justify-content-around {

&#x20; justify-content: space-around !important;

}



.justify-content-evenly {

&#x20; justify-content: space-evenly !important;

}



.align-items-start {

&#x20; align-items: flex-start !important;

}



.align-items-end {

&#x20; align-items: flex-end !important;

}



.align-items-center {

&#x20; alinhamento-itens: centralizado !importante;

}



.align-items-baseline {

&#x20; align-items: baseline !important;

}



.align-items-stretch {

&#x20; align-items: stretch !important;

}



.align-content-start {

&#x20; align-content: flex-start !important;

}



.align-content-end {

&#x20; align-content: flex-end !important;

}



.align-content-center {

&#x20; alinhamento-conteúdo: centralizado !importante;

}



.align-content-between {

&#x20; align-content: space-between !important;

}



.align-content-around {

&#x20; align-content: space-around !important;

}



.align-content-stretch {

&#x20; align-content: stretch !important;

}



.align-self-auto {

&#x20; alinhamento-próprio: automático !importante;

}



.alinhar-autoiniciar {

&#x20; align-self: flex-start !important;

}



.align-self-end {

&#x20; align-self: flex-end !important;

}



.align-self-center {

&#x20; alinhamento-próprio: centro !importante;

}



.align-self-baseline {

&#x20; alinhamento-próprio: linha de base !importante;

}



.align-self-stretch {

&#x20; alinhamento-próprio: esticar !importante;

}



.order-first {

&#x20; ordem: -1 !importante;

}



.order-0 {

&#x20; ordem: 0 !importante;

}



.order-1 {

&#x20; ordem: 1 !importante;

}



.order-2 {

&#x20; ordem: 2 !importante;

}



.order-3 {

&#x20; ordem: 3 !importante;

}



.order-4 {

&#x20; ordem: 4 !importante;

}



.order-5 {

&#x20; ordem: 5 !importante;

}



.order-last {

&#x20; ordem: 6 !importante;

}



.m-0 {

&#x20; margem: 0 !importante;

}



.m-1 {

&#x20; margem: 0,25rem !importante;

}



.m-2 {

&#x20; margem: 0,5rem !importante;

}



.m-3 {

&#x20; margem: 1rem !importante;

}



.m-4 {

&#x20; margem: 1,5rem !importante;

}



.m-5 {

&#x20; margem: 3rem !importante;

}



.m-auto {

&#x20; margem: automática !importante;

}



.mx-0 {

&#x20; margem-direita: 0 !importante;

&#x20; margem-esquerda: 0 !importante;

}



.mx-1 {

&#x20; margem-direita: 0,25rem !importante;

&#x20; margem-esquerda: 0,25rem !importante;

}



.mx-2 {

&#x20; margem-direita: 0,5rem !importante;

&#x20; margem-esquerda: 0,5rem !importante;

}



.mx-3 {

&#x20; margem-direita: 1rem !importante;

&#x20; margem-esquerda: 1rem !importante;

}



.mx-4 {

&#x20; margem-direita: 1,5rem !importante;

&#x20; margem-esquerda: 1,5rem !importante;

}



.mx-5 {

&#x20; margem-direita: 3rem !importante;

&#x20; margem-esquerda: 3rem !importante;

}



.mx-auto {

&#x20; margem-direita: auto !importante;

&#x20; margem-esquerda: auto !importante;

}



.meu-0 {

&#x20; margem-superior: 0 !importante;

&#x20; margem-inferior: 0 !importante;

}



.meu-1 {

&#x20; margem-superior: 0,25rem !importante;

&#x20; margem-inferior: 0,25rem !importante;

}



.meu-2 {

&#x20; margem-superior: 0,5rem !importante;

&#x20; margem-inferior: 0,5rem !importante;

}



.my-3 {

&#x20; margem-superior: 1rem !importante;

&#x20; margem-inferior: 1rem !importante;

}



.my-4 {

&#x20; margem-superior: 1,5rem !importante;

&#x20; margem-inferior: 1,5rem !importante;

}



.my-5 {

&#x20; margem-superior: 3rem !importante;

&#x20; margem-inferior: 3rem !importante;

}



.meu-automóvel {

&#x20; margem-superior: auto !importante;

&#x20; margem-inferior: auto !importante;

}



.mt-0 {

&#x20; margem-superior: 0 !importante;

}



.mt-1 {

&#x20; margem-superior: 0,25rem !importante;

}



.mt-2 {

&#x20; margem-superior: 0,5rem !importante;

}



.mt-3 {

&#x20; margem-superior: 1rem !importante;

}



.mt-4 {

&#x20; margem-superior: 1,5rem !importante;

}



.mt-5 {

&#x20; margem-superior: 3rem !importante;

}



.mt-auto {

&#x20; margem-superior: auto !importante;

}



.me-0 {

&#x20; margem-direita: 0 !importante;

}



.me-1 {

&#x20; margem-direita: 0,25rem !importante;

}



.me-2 {

&#x20; margem-direita: 0,5rem !importante;

}



.me-3 {

&#x20; margem-direita: 1rem !importante;

}



.me-4 {

&#x20; margem-direita: 1,5rem !importante;

}



.me-5 {

&#x20; margem-direita: 3rem !importante;

}



.me-auto {

&#x20; margem-direita: auto !importante;

}



.mb-0 {

&#x20; margem-inferior: 0 !importante;

}



.mb-1 {

&#x20; margem-inferior: 0,25rem !importante;

}



.mb-2 {

&#x20; margem-inferior: 0,5rem !importante;

}



.mb-3 {

&#x20; margem-inferior: 1rem !importante;

}



.mb-4 {

&#x20; margem-inferior: 1,5rem !importante;

}



.mb-5 {

&#x20; margem-inferior: 3rem !importante;

}



.mb-auto {

&#x20; margem-inferior: auto !importante;

}



.ms-0 {

&#x20; margem-esquerda: 0 !importante;

}



.ms-1 {

&#x20; margem-esquerda: 0,25rem !importante;

}



.ms-2 {

&#x20; margem-esquerda: 0,5rem !importante;

}



.ms-3 {

&#x20; margem-esquerda: 1rem !importante;

}



.ms-4 {

&#x20; margem-esquerda: 1,5rem !importante;

}



.ms-5 {

&#x20; margem-esquerda: 3rem !importante;

}



.ms-auto {

&#x20; margem-esquerda: auto !importante;

}



.p-0 {

&#x20; preenchimento: 0 !importante;

}



.p-1 {

&#x20; preenchimento: 0,25rem !importante;

}



.p-2 {

&#x20; preenchimento: 0,5rem !importante;

}



.p-3 {

&#x20; preenchimento: 1rem !importante;

}



.p-4 {

&#x20; preenchimento: 1,5rem !importante;

}



.p-5 {

&#x20; preenchimento: 3rem !importante;

}



.px-0 {

&#x20; padding-right: 0 !important;

&#x20; preenchimento-esquerdo: 0 !importante;

}



.px-1 {

&#x20; padding-right: 0.25rem !important;

&#x20; padding-left: 0.25rem !important;

}



.px-2 {

&#x20; padding-right: 0.5rem !important;

&#x20; padding-left: 0.5rem !important;

}



.px-3 {

&#x20; padding-right: 1rem !important;

&#x20; padding-left: 1rem !important;

}



.px-4 {

&#x20; padding-right: 1.5rem !important;

&#x20; padding-left: 1.5rem !important;

}



.px-5 {

&#x20; padding-right: 3rem !important;

&#x20; padding-left: 3rem !important;

}



.py-0 {

&#x20; padding-top: 0 !important;

&#x20; padding-bottom: 0 !important;

}



.py-1 {

&#x20; padding-top: 0.25rem !important;

&#x20; padding-bottom: 0.25rem !important;

}



.py-2 {

&#x20; padding-top: 0.5rem !important;

&#x20; padding-bottom: 0.5rem !important;

}



.py-3 {

&#x20; padding-top: 1rem !important;

&#x20; padding-bottom: 1rem !important;

}



.py-4 {

&#x20; padding-top: 1.5rem !important;

&#x20; padding-bottom: 1.5rem !important;

}



.py-5 {

&#x20; padding-top: 3rem !important;

&#x20; padding-bottom: 3rem !important;

}



.pt-0 {

&#x20; padding-top: 0 !important;

}



.pt-1 {

&#x20; padding-top: 0.25rem !important;

}



.pt-2 {

&#x20; padding-top: 0.5rem !important;

}



.pt-3 {

&#x20; padding-top: 1rem !important;

}



.pt-4 {

&#x20; padding-top: 1.5rem !important;

}



.pt-5 {

&#x20; padding-top: 3rem !important;

}



.pe-0 {

&#x20; padding-right: 0 !important;

}



.pe-1 {

&#x20; padding-right: 0.25rem !important;

}



.pe-2 {

&#x20; padding-right: 0.5rem !important;

}



.pe-3 {

&#x20; padding-right: 1rem !important;

}



.pe-4 {

&#x20; padding-right: 1.5rem !important;

}



.pe-5 {

&#x20; padding-right: 3rem !important;

}



.pb-0 {

&#x20; padding-bottom: 0 !important;

}



.pb-1 {

&#x20; padding-bottom: 0.25rem !important;

}



.pb-2 {

&#x20; padding-bottom: 0.5rem !important;

}



.pb-3 {

&#x20; padding-bottom: 1rem !important;

}



.pb-4 {

&#x20; padding-bottom: 1.5rem !important;

}



.pb-5 {

&#x20; padding-bottom: 3rem !important;

}



.ps-0 {

&#x20; preenchimento-esquerdo: 0 !importante;

}



.ps-1 {

&#x20; padding-left: 0.25rem !important;

}



.ps-2 {

&#x20; padding-left: 0.5rem !important;

}



.ps-3 {

&#x20; padding-left: 1rem !important;

}



.ps-4 {

&#x20; padding-left: 1.5rem !important;

}



.ps-5 {

&#x20; padding-left: 3rem !important;

}



.gap-0 {

&#x20; lacuna: 0 !importante;

}



.gap-1 {

&#x20; espaço: 0,25rem !importante;

}



.gap-2 {

&#x20; espaço: 0,5rem !importante;

}



.gap-3 {

&#x20; espaço: 1rem !importante;

}



.gap-4 {

&#x20; espaço: 1,5rem !importante;

}



.gap-5 {

&#x20; espaço: 3rem !importante;

}



.row-gap-0 {

&#x20; espaçamento entre linhas: 0 !importante;

}



.row-gap-1 {

&#x20; espaçamento entre linhas: 0,25rem !importante;

}



.row-gap-2 {

&#x20; espaçamento entre linhas: 0,5rem !importante;

}



.row-gap-3 {

&#x20; espaçamento entre linhas: 1rem !importante;

}



.row-gap-4 {

&#x20; espaçamento entre linhas: 1,5rem !importante;

}



.row-gap-5 {

&#x20; espaçamento entre linhas: 3rem !importante;

}



.espaçamento-coluna-0 {

&#x20; -moz-column-gap: 0 !important;

&#x20; espaçamento entre colunas: 0 !importante;

}



.espaçamento-coluna-1 {

&#x20; -moz-column-gap: 0.25rem !important;

&#x20; espaçamento entre colunas: 0,25rem !importante;

}



.espaçamento-coluna-2 {

&#x20; -moz-column-gap: 0.5rem !important;

&#x20; espaçamento entre colunas: 0,5rem !importante;

}



.column-gap-3 {

&#x20; -moz-column-gap: 1rem !important;

&#x20; column-gap: 1rem !important;

}



.espaçamento-coluna-4 {

&#x20; -moz-column-gap: 1.5rem !important;

&#x20; espaçamento entre colunas: 1,5rem !importante;

}



.column-gap-5 {

&#x20; -moz-column-gap: 3rem !important;

&#x20; column-gap: 3rem !important;

}



.font-monospace {

&#x20; família-fonte: var(--bs-font-monospace) !importante;

}



.fs-1 {

&#x20; tamanho-da-fonte: calc(1.375rem + 1.5vw) !importante;

}



.fs-2 {

&#x20; tamanho-da-fonte: calc(1.325rem + 0.9vw) !importante;

}



.fs-3 {

&#x20; tamanho-da-fonte: calc(1.3rem + 0.6vw) !importante;

}



.fs-4 {

&#x20; tamanho-da-fonte: calc(1.275rem + 0.3vw) !importante;

}



.fs-5 {

&#x20; tamanho da fonte: 1,25rem !importante;

}



.fs-6 {

&#x20; tamanho da fonte: 1rem !importante;

}



.fst-italic {

&#x20; estilo-da-fonte: itálico !importante;

}



.fst-normal {

&#x20; estilo-da-fonte: normal !importante;

}



.fw-lighter {

&#x20; peso da fonte: mais leve !importante;

}



.fw-light {

&#x20; peso da fonte: 300 !importante;

}



.fw-normal {

&#x20; peso da fonte: 400 !importante;

}



.fw-médio {

&#x20; peso da fonte: 500 !importante;

}



.fw-semibold {

&#x20; peso da fonte: 600 !importante;

}



.fw-bold {

&#x20; peso da fonte: 700 !importante;

}



.fw-bolder {

&#x20; peso da fonte: negrito !importante;

}



.lh-1 {

&#x20; altura-da-linha: 1 !importante;

}



.lh-sm {

&#x20; altura da linha: 1,25 !importante;

}



.lh-base {

&#x20; altura da linha: 1,5 !importante;

}



.lh-lg {

&#x20; altura-da-linha: 2 !importante;

}



.text-start {

&#x20; alinhamento de texto: esquerda !importante;

}



.text-end {

&#x20; alinhamento de texto: direita !importante;

}



.text-center {

&#x20; alinhamento de texto: centralizado !importante;

}



.text-decoration-none {

&#x20; text-decoration: none !important;

}



.text-decoration-underline {

&#x20; text-decoration: underline !important;

}



.text-decoration-line-through {

&#x20; text-decoration: line-through !important;

}



.text-lowercase {

&#x20; text-transform: lowercase !important;

}



.text-uppercase {

&#x20; text-transform: uppercase !important;

}



.text-capitalize {

&#x20; text-transform: capitalize !important;

}



.text-wrap {

&#x20; espaço em branco: normal !importante;

}



.text-nowrap {

&#x20; white-space: nowrap !important;

}



/\* rtl:begin:remove \*/

.text-break {

&#x20; quebra-de-palavra: quebra-de-palavra !importante;

&#x20; quebra-de-palavra: quebra-de-palavra !importante;

}



/\* rtl:end:remove \*/

.texto-primário {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-primary-rgb), var(--bs-text-opacity)) !importante;

}



.texto-secundário {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-secondary-rgb), var(--bs-text-opacity)) !importante;

}



.text-sucesso {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-success-rgb), var(--bs-text-opacity)) !importante;

}



.text-info {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-info-rgb), var(--bs-text-opacity)) !importante;

}



.text-warning {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-warning-rgb), var(--bs-text-opacity)) !importante;

}



.text-danger {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-danger-rgb), var(--bs-text-opacity)) !importante;

}



.text-light {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-light-rgb), var(--bs-text-opacity)) !importante;

}



.text-dark {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-dark-rgb), var(--bs-text-opacity)) !importante;

}



.text-preto {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-black-rgb), var(--bs-text-opacity)) !importante;

}



.text-white {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-white-rgb), var(--bs-text-opacity)) !importante;

}



.text-body {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(var(--bs-body-color-rgb), var(--bs-text-opacity)) !importante;

}



.text-muted {

&#x20; --bs-text-opacity: 1;

&#x20; cor: var(--bs-secondary-color) !important;

}



.text-black-50 {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(0, 0, 0, 0.5) !importante;

}



.text-white-50 {

&#x20; --bs-text-opacity: 1;

&#x20; cor: rgba(255, 255, 255, 0.5) !importante;

}



.text-body-secondary {

&#x20; --bs-text-opacity: 1;

&#x20; cor: var(--bs-secondary-color) !important;

}



.text-body-tertiary {

&#x20; --bs-text-opacity: 1;

&#x20; cor: var(--bs-tertiary-color) !importante;

}



.text-body-emphasis {

&#x20; --bs-text-opacity: 1;

&#x20; cor: var(--bs-emphasis-color) !importante;

}



.text-reset {

&#x20; --bs-text-opacity: 1;

&#x20; cor: herdar !importante;

}



.text-opacity-25 {

&#x20; --bs-text-opacity: 0.25;

}



.text-opacity-50 {

&#x20; --bs-text-opacity: 0.5;

}



.text-opacity-75 {

&#x20; --bs-text-opacity: 0.75;

}



.text-opacity-100 {

&#x20; --bs-text-opacity: 1;

}



.text-primary-emphasis {

&#x20; cor: var(--bs-primary-text-emphasis) !important;

}



.text-secondary-emphasis {

&#x20; cor: var(--bs-secondary-text-emphasis) !important;

}



.text-success-emphasis {

&#x20; cor: var(--bs-success-text-emphasis) !importante;

}



.text-info-emphasis {

&#x20; cor: var(--bs-info-text-emphasis) !importante;

}



.text-warning-emphasis {

&#x20; cor: var(--bs-warning-text-emphasis) !importante;

}



.text-danger-emphasis {

&#x20; cor: var(--bs-danger-text-emphasis) !importante;

}



.text-light-emphasis {

&#x20; cor: var(--bs-light-text-emphasis) !importante;

}



.text-dark-emphasis {

&#x20; cor: var(--bs-dark-text-emphasis) !importante;

}



.link-opacity-10 {

&#x20; --bs-link-opacity: 0.1;

}



.link-opacity-10-hover:hover {

&#x20; --bs-link-opacity: 0.1;

}



.link-opacity-25 {

&#x20; --bs-link-opacity: 0.25;

}



.link-opacity-25-hover:hover {

&#x20; --bs-link-opacity: 0.25;

}



.link-opacity-50 {

&#x20; --bs-link-opacity: 0.5;

}



.link-opacity-50-hover:hover {

&#x20; --bs-link-opacity: 0.5;

}



.link-opacity-75 {

&#x20; --bs-link-opacity: 0.75;

}



.link-opacity-75-hover:hover {

&#x20; --bs-link-opacity: 0.75;

}



.link-opacity-100 {

&#x20; --bs-link-opacity: 1;

}



.link-opacity-100-hover:hover {

&#x20; --bs-link-opacity: 1;

}



.link-offset-1 {

&#x20; text-underline-offset: 0.125em !important;

}



.link-offset-1-hover:hover {

&#x20; text-underline-offset: 0.125em !important;

}



.link-offset-2 {

&#x20; text-underline-offset: 0.25em !important;

}



.link-offset-2-hover:hover {

&#x20; text-underline-offset: 0.25em !important;

}



.link-offset-3 {

&#x20; text-underline-offset: 0.375em !important;

}



.link-offset-3-hover:hover {

&#x20; text-underline-offset: 0.375em !important;

}



.link-underline-primary {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-primary-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-primary-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline-secondary {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-secondary-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-secondary-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline-success {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-success-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-success-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline-info {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-info-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-info-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline-warning {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-warning-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-warning-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline-danger {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-danger-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-danger-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline-light {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-light-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-light-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline-dark {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-dark-rgb), var(--bs-link-underline-opacity)) !important;

&#x20; cor-decoração-texto: rgba(var(--bs-dark-rgb), var(--bs-link-underline-opacity)) !importante;

}



.link-underline {

&#x20; --bs-link-underline-opacity: 1;

&#x20; -webkit-text-decoration-color: rgba(var(--bs-link-color-rgb), var(--bs-link-underline-opacity, 1)) !important;

&#x20; text-decoration-color: rgba(var(--bs-link-color-rgb), var(--bs-link-underline-opacity, 1)) !important;

}



.link-underline-opacity-0 {

&#x20; --bs-link-underline-opacity: 0;

}



.link-underline-opacity-0-hover:hover {

&#x20; --bs-link-underline-opacity: 0;

}



.link-underline-opacity-10 {

&#x20; --bs-link-underline-opacity: 0.1;

}



.link-underline-opacity-10-hover:hover {

&#x20; --bs-link-underline-opacity: 0.1;

}



.link-underline-opacity-25 {

&#x20; --bs-link-underline-opacity: 0.25;

}



.link-underline-opacity-25-hover:hover {

&#x20; --bs-link-underline-opacity: 0.25;

}



.link-underline-opacity-50 {

&#x20; --bs-link-underline-opacity: 0.5;

}



.link-underline-opacity-50-hover:hover {

&#x20; --bs-link-underline-opacity: 0.5;

}



.link-underline-opacity-75 {

&#x20; --bs-link-underline-opacity: 0.75;

}



.link-underline-opacity-75-hover:hover {

&#x20; --bs-link-underline-opacity: 0.75;

}



.link-underline-opacity-100 {

&#x20; --bs-link-underline-opacity: 1;

}



.link-underline-opacity-100-hover:hover {

&#x20; --bs-link-underline-opacity: 1;

}



.bg-primary {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-primary-rgb), var(--bs-bg-opacity)) !important;

}



.bg-secundário {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-secondary-rgb), var(--bs-bg-opacity)) !important;

}



.bg-sucesso {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-success-rgb), var(--bs-bg-opacity)) !important;

}



.bg-info {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-info-rgb), var(--bs-bg-opacity)) !important;

}



.bg-warning {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-warning-rgb), var(--bs-bg-opacity)) !important;

}



.bg-danger {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-danger-rgb), var(--bs-bg-opacity)) !important;

}



.bg-light {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-light-rgb), var(--bs-bg-opacity)) !important;

}



.bg-dark {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-dark-rgb), var(--bs-bg-opacity)) !important;

}



.bg-preto {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-black-rgb), var(--bs-bg-opacity)) !important;

}



.bg-branco {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-white-rgb), var(--bs-bg-opacity)) !important;

}



.bg-body {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-body-bg-rgb), var(--bs-bg-opacity)) !important;

}



.bg-transparente {

&#x20; --bs-bg-opacity: 1;

&#x20; cor de fundo: transparente !importante;

}



.bg-body-secondary {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-secondary-bg-rgb), var(--bs-bg-opacity)) !important;

}



.bg-body-terciário {

&#x20; --bs-bg-opacity: 1;

&#x20; background-color: rgba(var(--bs-tertiary-bg-rgb), var(--bs-bg-opacity)) !important;

}



.bg-opacity-10 {

&#x20; --bs-bg-opacity: 0.1;

}



.bg-opacity-25 {

&#x20; --bs-bg-opacity: 0.25;

}



.bg-opacity-50 {

&#x20; --bs-bg-opacity: 0.5;

}



.bg-opacity-75 {

&#x20; --bs-bg-opacity: 0.75;

}



.bg-opacity-100 {

&#x20; --bs-bg-opacity: 1;

}



.bg-primary-subtle {

&#x20; cor de fundo: var(--bs-primary-bg-subtle) !importante;

}



.bg-secondary-subtle {

&#x20; background-color: var(--bs-secondary-bg-subtle) !important;

}



.bg-sucesso-sutil {

&#x20; background-color: var(--bs-success-bg-subtle) !important;

}



.bg-info-subtle {

&#x20; cor de fundo: var(--bs-info-bg-subtle) !importante;

}



.bg-warning-subtle {

&#x20; background-color: var(--bs-warning-bg-subtle) !important;

}



.bg-danger-subtle {

&#x20; cor de fundo: var(--bs-danger-bg-subtle) !importante;

}



.bg-light-subtle {

&#x20; cor de fundo: var(--bs-light-bg-subtle) !importante;

}



.bg-dark-subtle {

&#x20; cor de fundo: var(--bs-dark-bg-subtle) !importante;

}



.bg-gradiente {

&#x20; background-image: var(--bs-gradient) !important;

}



.user-select-all {

&#x20; -webkit-user-select: tudo !importante;

&#x20; -moz-user-select: tudo !importante;

&#x20; seleção do usuário: tudo !importante;

}



.user-select-auto {

&#x20; -webkit-user-select: auto !important;

&#x20; -moz-user-select: auto !important;

&#x20; seleção do usuário: automático !importante;

}



.user-select-none {

&#x20; -webkit-user-select: nenhum !importante;

&#x20; -moz-user-select: nenhum !importante;

&#x20; seleção do usuário: nenhum !importante;

}



.pe-nenhum {

&#x20; eventos-ponteiro: nenhum !importante;

}



.pe-auto {

&#x20; eventos-ponteiro: auto !importante;

}



.arredondado {

&#x20; raio da borda: var(--bs-raio da borda) !importante;

}



.rounded-0 {

&#x20; raio-da-borda: 0 !importante;

}



.rounded-1 {

&#x20; border-radius: var(--bs-border-radius-sm) !important;

}



.rounded-2 {

&#x20; raio da borda: var(--bs-raio da borda) !importante;

}



.rounded-3 {

&#x20; raio da borda: var(--bs-border-radius-lg) !importante;

}



.rounded-4 {

&#x20; border-radius: var(--bs-border-radius-xl) !important;

}



.rounded-5 {

&#x20; border-radius: var(--bs-border-radius-xxl) !important;

}



.círculo-arredondado {

&#x20; raio-da-borda: 50% !importante;

}



.pílula-arredondada {

&#x20; raio da borda: var(--bs-border-radius-pill) !importante;

}



.topo arredondado {

&#x20; border-top-left-radius: var(--bs-border-radius) !important;

&#x20; border-top-right-radius: var(--bs-border-radius) !important;

}



.rounded-top-0 {

&#x20; raio-superior-esquerdo-da-borda: 0 !importante;

&#x20; border-top-right-radius: 0 !important;

}



.rounded-top-1 {

&#x20; border-top-left-radius: var(--bs-border-radius-sm) !important;

&#x20; border-top-right-radius: var(--bs-border-radius-sm) !important;

}



.rounded-top-2 {

&#x20; border-top-left-radius: var(--bs-border-radius) !important;

&#x20; border-top-right-radius: var(--bs-border-radius) !important;

}



.rounded-top-3 {

&#x20; border-top-left-radius: var(--bs-border-radius-lg) !important;

&#x20; border-top-right-radius: var(--bs-border-radius-lg) !important;

}



.rounded-top-4 {

&#x20; border-top-left-radius: var(--bs-border-radius-xl) !important;

&#x20; border-top-right-radius: var(--bs-border-radius-xl) !important;

}



.rounded-top-5 {

&#x20; border-top-left-radius: var(--bs-border-radius-xxl) !important;

&#x20; border-top-right-radius: var(--bs-border-radius-xxl) !important;

}



.círculo-arredondado-no-topo {

&#x20; raio-superior-esquerdo-da-borda: 50% !importante;

&#x20; border-top-right-radius: 50% !important;

}



.pílula-de-topo-arredondado {

&#x20; border-top-left-radius: var(--bs-border-radius-pill) !important;

&#x20; border-top-right-radius: var(--bs-border-radius-pill) !important;

}



.rounded-end {

&#x20; border-top-right-radius: var(--bs-border-radius) !important;

&#x20; border-bottom-right-radius: var(--bs-border-radius) !important;

}



.rounded-end-0 {

&#x20; border-top-right-radius: 0 !important;

&#x20; raio-inferior-direito-da-borda: 0 !importante;

}



.rounded-end-1 {

&#x20; border-top-right-radius: var(--bs-border-radius-sm) !important;

&#x20; border-bottom-right-radius: var(--bs-border-radius-sm) !important;

}



.rounded-end-2 {

&#x20; border-top-right-radius: var(--bs-border-radius) !important;

&#x20; border-bottom-right-radius: var(--bs-border-radius) !important;

}



.rounded-end-3 {

&#x20; border-top-right-radius: var(--bs-border-radius-lg) !important;

&#x20; border-bottom-right-radius: var(--bs-border-radius-lg) !important;

}



.rounded-end-4 {

&#x20; border-top-right-radius: var(--bs-border-radius-xl) !important;

&#x20; border-bottom-right-radius: var(--bs-border-radius-xl) !important;

}



.rounded-end-5 {

&#x20; border-top-right-radius: var(--bs-border-radius-xxl) !important;

&#x20; border-bottom-right-radius: var(--bs-border-radius-xxl) !important;

}



.círculo-com-extremidades-arredondadas {

&#x20; border-top-right-radius: 50% !important;

&#x20; raio-inferior-direito-da-borda: 50% !importante;

}



.pílula-de-ponta-arredondada {

&#x20; border-top-right-radius: var(--bs-border-radius-pill) !important;

&#x20; border-bottom-right-radius: var(--bs-border-radius-pill) !important;

}



.rounded-bottom {

&#x20; border-bottom-right-radius: var(--bs-border-radius) !important;

&#x20; border-bottom-left-radius: var(--bs-border-radius) !important;

}



.rounded-bottom-0 {

&#x20; raio-inferior-direito-da-borda: 0 !importante;

&#x20; raio-inferior-esquerdo-da-borda: 0 !importante;

}



.rounded-bottom-1 {

&#x20; border-bottom-right-radius: var(--bs-border-radius-sm) !important;

&#x20; border-bottom-left-radius: var(--bs-border-radius-sm) !important;

}



.rounded-bottom-2 {

&#x20; border-bottom-right-radius: var(--bs-border-radius) !important;

&#x20; border-bottom-left-radius: var(--bs-border-radius) !important;

}



.rounded-bottom-3 {

&#x20; border-bottom-right-radius: var(--bs-border-radius-lg) !important;

&#x20; border-bottom-left-radius: var(--bs-border-radius-lg) !important;

}



.rounded-bottom-4 {

&#x20; border-bottom-right-radius: var(--bs-border-radius-xl) !important;

&#x20; border-bottom-left-radius: var(--bs-border-radius-xl) !important;

}



.rounded-bottom-5 {

&#x20; border-bottom-right-radius: var(--bs-border-radius-xxl) !important;

&#x20; border-bottom-left-radius: var(--bs-border-radius-xxl) !important;

}



.círculo-arredondado-na-base {

&#x20; raio-inferior-direito-da-borda: 50% !importante;

&#x20; raio-inferior-esquerdo-da-borda: 50% !importante;

}



.pílula-de-fundo-arredondado {

&#x20; border-bottom-right-radius: var(--bs-border-radius-pill) !important;

&#x20; border-bottom-left-radius: var(--bs-border-radius-pill) !important;

}



.início arredondado {

&#x20; border-bottom-left-radius: var(--bs-border-radius) !important;

&#x20; border-top-left-radius: var(--bs-border-radius) !important;

}



.rounded-start-0 {

&#x20; raio-inferior-esquerdo-da-borda: 0 !importante;

&#x20; raio-superior-esquerdo-da-borda: 0 !importante;

}



.rounded-start-1 {

&#x20; border-bottom-left-radius: var(--bs-border-radius-sm) !important;

&#x20; border-top-left-radius: var(--bs-border-radius-sm) !important;

}



.rounded-start-2 {

&#x20; border-bottom-left-radius: var(--bs-border-radius) !important;

&#x20; border-top-left-radius: var(--bs-border-radius) !important;

}



.rounded-start-3 {

&#x20; border-bottom-left-radius: var(--bs-border-radius-lg) !important;

&#x20; border-top-left-radius: var(--bs-border-radius-lg) !important;

}



.rounded-start-4 {

&#x20; border-bottom-left-radius: var(--bs-border-radius-xl) !important;

&#x20; border-top-left-radius: var(--bs-border-radius-xl) !important;

}



.rounded-start-5 {

&#x20; border-bottom-left-radius: var(--bs-border-radius-xxl) !important;

&#x20; border-top-left-radius: var(--bs-border-radius-xxl) !important;

}



.círculo-inicial-arredondado {

&#x20; raio-inferior-esquerdo-da-borda: 50% !importante;

&#x20; raio-superior-esquerdo-da-borda: 50% !importante;

}



.pílula-inicial-arredondada {

&#x20; border-bottom-left-radius: var(--bs-border-radius-pill) !important;

&#x20; border-top-left-radius: var(--bs-border-radius-pill) !important;

}



.visível {

&#x20; visibilidade: visível !importante;

}



.invisível {

&#x20; visibilidade: oculto !importante;

}



.z-n1 {

&#x20; z-index: -1 !importante;

}



.z-0 {

&#x20; z-index: 0 !importante;

}



.z-1 {

&#x20; z-index: 1 !importante;

}



.z-2 {

&#x20; z-index: 2 !importante;

}



.z-3 {

&#x20; z-index: 3 !importante;

}



@media (min-width: 576px) {

&#x20; .float-sm-start {

&#x20;   flutuar: esquerda !importante;

&#x20; }

&#x20; .float-sm-end {

&#x20;   flutuar: direita !importante;

&#x20; }

&#x20; .float-sm-none {

&#x20;   flutuar: nenhum !importante;

&#x20; }

&#x20; .object-fit-sm-contain {

&#x20;   -o-object-fit: contém !importante;

&#x20;   object-fit: conter !important;

&#x20; }

&#x20; .object-fit-sm-cover {

&#x20;   -o-object-fit: cobrir !importante;

&#x20;   object-fit: cobrir !importante;

&#x20; }

&#x20; .object-fit-sm-fill {

&#x20;   -o-object-fit: preencher !importante;

&#x20;   object-fit: preencher !important;

&#x20; }

&#x20; .object-fit-sm-scale {

&#x20;   -o-object-fit: reduzir a escala !importante;

&#x20;   object-fit: reduzir escala !important;

&#x20; }

&#x20; .object-fit-sm-none {

&#x20;   -o-object-fit: nenhum !importante;

&#x20;   object-fit: none !important;

&#x20; }

&#x20; .d-sm-inline {

&#x20;   exibir: embutido !importante;

&#x20; }

&#x20; .d-sm-inline-block {

&#x20;   exibir: inline-block !important;

&#x20; }

&#x20; .d-sm-block {

&#x20;   exibir: bloco !importante;

&#x20; }

&#x20; .d-sm-grid {

&#x20;   exibir: grade !importante;

&#x20; }

&#x20; .d-sm-inline-grid {

&#x20;   exibição: grade em linha !importante;

&#x20; }

&#x20; .d-sm-table {

&#x20;   exibir: tabela !importante;

&#x20; }

&#x20; .d-sm-table-row {

&#x20;   exibir: linha-da-tabela !importante;

&#x20; }

&#x20; .d-sm-table-cell {

&#x20;   exibir: célula-da-tabela !importante;

&#x20; }

&#x20; .d-sm-flex {

&#x20;   exibir: flex !importante;

&#x20; }

&#x20; .d-sm-inline-flex {

&#x20;   exibir: inline-flex !important;

&#x20; }

&#x20; .d-sm-nenhum {

&#x20;   exibir: nenhum !importante;

&#x20; }

&#x20; .flex-sm-fill {

&#x20;   flex: 1 1 auto !importante;

&#x20; }

&#x20; .flex-sm-row {

&#x20;   flex-direction: linha !importante;

&#x20; }

&#x20; .flex-sm-column {

&#x20;   flex-direction: coluna !importante;

&#x20; }

&#x20; .flex-sm-row-reverse {

&#x20;   flex-direction: row-reverse !important;

&#x20; }

&#x20; .flex-sm-column-reverse {

&#x20;   flex-direction: column-reverse !important;

&#x20; }

&#x20; .flex-sm-grow-0 {

&#x20;   flex-grow: 0 !importante;

&#x20; }

&#x20; .flex-sm-grow-1 {

&#x20;   flex-grow: 1 !importante;

&#x20; }

&#x20; .flex-sm-shrink-0 {

&#x20;   flex-shrink: 0 !importante;

&#x20; }

&#x20; .flex-sm-shrink-1 {

&#x20;   flex-shrink: 1 !importante;

&#x20; }

&#x20; .flex-sm-wrap {

&#x20;   flex-wrap: envolver !importante;

&#x20; }

&#x20; .flex-sm-nowrap {

&#x20;   flex-wrap: nowrap !important;

&#x20; }

&#x20; .flex-sm-wrap-reverse {

&#x20;   flex-wrap: wrap-reverse !important;

&#x20; }

&#x20; .justify-content-sm-start {

&#x20;   justify-content: flex-start !important;

&#x20; }

&#x20; .justify-content-sm-end {

&#x20;   justify-content: flex-end !important;

&#x20; }

&#x20; .justify-content-sm-center {

&#x20;   justify-content: center !important;

&#x20; }

&#x20; .justify-content-sm-between {

&#x20;   justify-content: espaço-entre !important;

&#x20; }

&#x20; .justify-content-sm-around {

&#x20;   justify-content: space-around !important;

&#x20; }

&#x20; .justify-content-sm-evenly {

&#x20;   justify-content: space-evenly !important;

&#x20; }

&#x20; .align-items-sm-start {

&#x20;   align-items: flex-start !important;

&#x20; }

&#x20; .align-items-sm-end {

&#x20;   align-items: flex-end !important;

&#x20; }

&#x20; .align-items-sm-center {

&#x20;   alinhamento-itens: centralizado !importante;

&#x20; }

&#x20; .align-items-sm-baseline {

&#x20;   align-items: baseline !important;

&#x20; }

&#x20; .align-items-sm-stretch {

&#x20;   align-items: stretch !important;

&#x20; }

&#x20; .align-content-sm-start {

&#x20;   align-content: flex-start !important;

&#x20; }

&#x20; .align-content-sm-end {

&#x20;   align-content: flex-end !important;

&#x20; }

&#x20; .align-content-sm-center {

&#x20;   alinhamento-conteúdo: centralizado !importante;

&#x20; }

&#x20; .align-content-sm-between {

&#x20;   align-content: space-between !important;

&#x20; }

&#x20; .align-content-sm-around {

&#x20;   align-content: space-around !important;

&#x20; }

&#x20; .align-content-sm-stretch {

&#x20;   align-content: stretch !important;

&#x20; }

&#x20; .align-self-sm-auto {

&#x20;   alinhamento-próprio: automático !importante;

&#x20; }

&#x20; .align-self-sm-start {

&#x20;   align-self: flex-start !important;

&#x20; }

&#x20; .align-self-sm-end {

&#x20;   align-self: flex-end !important;

&#x20; }

&#x20; .align-self-sm-center {

&#x20;   alinhamento-próprio: centro !importante;

&#x20; }

&#x20; .align-self-sm-baseline {

&#x20;   alinhamento-próprio: linha de base !importante;

&#x20; }

&#x20; .align-self-sm-stretch {

&#x20;   alinhamento-próprio: esticar !importante;

&#x20; }

&#x20; .order-sm-first {

&#x20;   ordem: -1 !importante;

&#x20; }

&#x20; .order-sm-0 {

&#x20;   ordem: 0 !importante;

&#x20; }

&#x20; .order-sm-1 {

&#x20;   ordem: 1 !importante;

&#x20; }

&#x20; .order-sm-2 {

&#x20;   ordem: 2 !importante;

&#x20; }

&#x20; .order-sm-3 {

&#x20;   ordem: 3 !importante;

&#x20; }

&#x20; .order-sm-4 {

&#x20;   ordem: 4 !importante;

&#x20; }

&#x20; .order-sm-5 {

&#x20;   ordem: 5 !importante;

&#x20; }

&#x20; .order-sm-last {

&#x20;   ordem: 6 !importante;

&#x20; }

&#x20; .m-sm-0 {

&#x20;   margem: 0 !importante;

&#x20; }

&#x20; .m-sm-1 {

&#x20;   margem: 0,25rem !importante;

&#x20; }

&#x20; .m-sm-2 {

&#x20;   margem: 0,5rem !importante;

&#x20; }

&#x20; .m-sm-3 {

&#x20;   margem: 1rem !importante;

&#x20; }

&#x20; .m-sm-4 {

&#x20;   margem: 1,5rem !importante;

&#x20; }

&#x20; .m-sm-5 {

&#x20;   margem: 3rem !importante;

&#x20; }

&#x20; .m-sm-auto {

&#x20;   margem: automática !importante;

&#x20; }

&#x20; .mx-sm-0 {

&#x20;   margem-direita: 0 !importante;

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .mx-sm-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .mx-sm-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .mx-sm-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .mx-sm-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .mx-sm-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .mx-sm-auto {

&#x20;   margem-direita: auto !importante;

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .my-sm-0 {

&#x20;   margem-superior: 0 !importante;

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .my-sm-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .my-sm-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .my-sm-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .my-sm-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .my-sm-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .my-sm-auto {

&#x20;   margem-superior: auto !importante;

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .mt-sm-0 {

&#x20;   margem-superior: 0 !importante;

&#x20; }

&#x20; .mt-sm-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20; }

&#x20; .mt-sm-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20; }

&#x20; .mt-sm-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20; }

&#x20; .mt-sm-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20; }

&#x20; .mt-sm-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20; }

&#x20; .mt-sm-auto {

&#x20;   margem-superior: auto !importante;

&#x20; }

&#x20; .me-sm-0 {

&#x20;   margem-direita: 0 !importante;

&#x20; }

&#x20; .me-sm-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20; }

&#x20; .me-sm-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20; }

&#x20; .me-sm-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20; }

&#x20; .me-sm-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20; }

&#x20; .me-sm-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20; }

&#x20; .me-sm-auto {

&#x20;   margem-direita: auto !importante;

&#x20; }

&#x20; .mb-sm-0 {

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .mb-sm-1 {

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .mb-sm-2 {

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .mb-sm-3 {

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .mb-sm-4 {

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .mb-sm-5 {

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .mb-sm-auto {

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .ms-sm-0 {

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .ms-sm-1 {

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .ms-sm-2 {

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .ms-sm-3 {

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .ms-sm-4 {

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .ms-sm-5 {

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .ms-sm-auto {

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .p-sm-0 {

&#x20;   preenchimento: 0 !importante;

&#x20; }

&#x20; .p-sm-1 {

&#x20;   preenchimento: 0,25rem !importante;

&#x20; }

&#x20; .p-sm-2 {

&#x20;   preenchimento: 0,5rem !importante;

&#x20; }

&#x20; .p-sm-3 {

&#x20;   preenchimento: 1rem !importante;

&#x20; }

&#x20; .p-sm-4 {

&#x20;   preenchimento: 1,5rem !importante;

&#x20; }

&#x20; .p-sm-5 {

&#x20;   preenchimento: 3rem !importante;

&#x20; }

&#x20; .px-sm-0 {

&#x20;   padding-right: 0 !important;

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .px-sm-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .px-sm-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .px-sm-3 {

&#x20;   padding-right: 1rem !important;

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .px-sm-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .px-sm-5 {

&#x20;   padding-right: 3rem !important;

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .py-sm-0 {

&#x20;   padding-top: 0 !important;

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .py-sm-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .py-sm-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .py-sm-3 {

&#x20;   padding-top: 1rem !important;

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .py-sm-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .py-sm-5 {

&#x20;   padding-top: 3rem !important;

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .pt-sm-0 {

&#x20;   padding-top: 0 !important;

&#x20; }

&#x20; .pt-sm-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20; }

&#x20; .pt-sm-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20; }

&#x20; .pt-sm-3 {

&#x20;   padding-top: 1rem !important;

&#x20; }

&#x20; .pt-sm-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20; }

&#x20; .pt-sm-5 {

&#x20;   padding-top: 3rem !important;

&#x20; }

&#x20; .pe-sm-0 {

&#x20;   padding-right: 0 !important;

&#x20; }

&#x20; .pe-sm-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20; }

&#x20; .pe-sm-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20; }

&#x20; .pe-sm-3 {

&#x20;   padding-right: 1rem !important;

&#x20; }

&#x20; .pe-sm-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20; }

&#x20; .pe-sm-5 {

&#x20;   padding-right: 3rem !important;

&#x20; }

&#x20; .pb-sm-0 {

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .pb-sm-1 {

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .pb-sm-2 {

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .pb-sm-3 {

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .pb-sm-4 {

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .pb-sm-5 {

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .ps-sm-0 {

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .ps-sm-1 {

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .ps-sm-2 {

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .ps-sm-3 {

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .ps-sm-4 {

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .ps-sm-5 {

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .gap-sm-0 {

&#x20;   lacuna: 0 !importante;

&#x20; }

&#x20; .gap-sm-1 {

&#x20;   espaço: 0,25rem !importante;

&#x20; }

&#x20; .gap-sm-2 {

&#x20;   espaço: 0,5rem !importante;

&#x20; }

&#x20; .gap-sm-3 {

&#x20;   espaço: 1rem !importante;

&#x20; }

&#x20; .gap-sm-4 {

&#x20;   espaço: 1,5rem !importante;

&#x20; }

&#x20; .gap-sm-5 {

&#x20;   espaço: 3rem !importante;

&#x20; }

&#x20; .row-gap-sm-0 {

&#x20;   espaçamento entre linhas: 0 !importante;

&#x20; }

&#x20; .row-gap-sm-1 {

&#x20;   espaçamento entre linhas: 0,25rem !importante;

&#x20; }

&#x20; .row-gap-sm-2 {

&#x20;   espaçamento entre linhas: 0,5rem !importante;

&#x20; }

&#x20; .row-gap-sm-3 {

&#x20;   espaçamento entre linhas: 1rem !importante;

&#x20; }

&#x20; .row-gap-sm-4 {

&#x20;   espaçamento entre linhas: 1,5rem !importante;

&#x20; }

&#x20; .row-gap-sm-5 {

&#x20;   espaçamento entre linhas: 3rem !importante;

&#x20; }

&#x20; .column-gap-sm-0 {

&#x20;   -moz-column-gap: 0 !important;

&#x20;   espaçamento entre colunas: 0 !importante;

&#x20; }

&#x20; .column-gap-sm-1 {

&#x20;   -moz-column-gap: 0.25rem !important;

&#x20;   espaçamento entre colunas: 0,25rem !importante;

&#x20; }

&#x20; .column-gap-sm-2 {

&#x20;   -moz-column-gap: 0.5rem !important;

&#x20;   espaçamento entre colunas: 0,5rem !importante;

&#x20; }

&#x20; .column-gap-sm-3 {

&#x20;   -moz-column-gap: 1rem !important;

&#x20;   column-gap: 1rem !important;

&#x20; }

&#x20; .column-gap-sm-4 {

&#x20;   -moz-column-gap: 1.5rem !important;

&#x20;   espaçamento entre colunas: 1,5rem !importante;

&#x20; }

&#x20; .column-gap-sm-5 {

&#x20;   -moz-column-gap: 3rem !important;

&#x20;   column-gap: 3rem !important;

&#x20; }

&#x20; .text-sm-start {

&#x20;   alinhamento de texto: esquerda !importante;

&#x20; }

&#x20; .text-sm-end {

&#x20;   alinhamento de texto: direita !importante;

&#x20; }

&#x20; .text-sm-center {

&#x20;   alinhamento de texto: centralizado !importante;

&#x20; }

}

@media (min-width: 768px) {

&#x20; .float-md-start {

&#x20;   flutuar: esquerda !importante;

&#x20; }

&#x20; .float-md-end {

&#x20;   flutuar: direita !importante;

&#x20; }

&#x20; .float-md-none {

&#x20;   flutuar: nenhum !importante;

&#x20; }

&#x20; .object-fit-md-contain {

&#x20;   -o-object-fit: contém !importante;

&#x20;   object-fit: conter !important;

&#x20; }

&#x20; .object-fit-md-cover {

&#x20;   -o-object-fit: cobrir !importante;

&#x20;   object-fit: cobrir !importante;

&#x20; }

&#x20; .object-fit-md-fill {

&#x20;   -o-object-fit: preencher !importante;

&#x20;   object-fit: preencher !important;

&#x20; }

&#x20; .object-fit-md-scale {

&#x20;   -o-object-fit: reduzir a escala !importante;

&#x20;   object-fit: reduzir escala !important;

&#x20; }

&#x20; .object-fit-md-none {

&#x20;   -o-object-fit: nenhum !importante;

&#x20;   object-fit: none !important;

&#x20; }

&#x20; .d-md-inline {

&#x20;   exibir: embutido !importante;

&#x20; }

&#x20; .d-md-inline-block {

&#x20;   exibir: inline-block !important;

&#x20; }

&#x20; .d-md-block {

&#x20;   exibir: bloco !importante;

&#x20; }

&#x20; .d-md-grid {

&#x20;   exibir: grade !importante;

&#x20; }

&#x20; .d-md-inline-grid {

&#x20;   exibição: grade em linha !importante;

&#x20; }

&#x20; .d-md-table {

&#x20;   exibir: tabela !importante;

&#x20; }

&#x20; .d-md-table-row {

&#x20;   exibir: linha-da-tabela !importante;

&#x20; }

&#x20; .d-md-table-cell {

&#x20;   exibir: célula-da-tabela !importante;

&#x20; }

&#x20; .d-md-flex {

&#x20;   exibir: flex !importante;

&#x20; }

&#x20; .d-md-inline-flex {

&#x20;   exibir: inline-flex !important;

&#x20; }

&#x20; .d-md-none {

&#x20;   exibir: nenhum !importante;

&#x20; }

&#x20; .flex-md-fill {

&#x20;   flex: 1 1 auto !importante;

&#x20; }

&#x20; .flex-md-row {

&#x20;   flex-direction: linha !importante;

&#x20; }

&#x20; .flex-md-column {

&#x20;   flex-direction: coluna !importante;

&#x20; }

&#x20; .flex-md-row-reverse {

&#x20;   flex-direction: row-reverse !important;

&#x20; }

&#x20; .flex-md-column-reverse {

&#x20;   flex-direction: column-reverse !important;

&#x20; }

&#x20; .flex-md-grow-0 {

&#x20;   flex-grow: 0 !importante;

&#x20; }

&#x20; .flex-md-grow-1 {

&#x20;   flex-grow: 1 !importante;

&#x20; }

&#x20; .flex-md-shrink-0 {

&#x20;   flex-shrink: 0 !importante;

&#x20; }

&#x20; .flex-md-shrink-1 {

&#x20;   flex-shrink: 1 !importante;

&#x20; }

&#x20; .flex-md-wrap {

&#x20;   flex-wrap: envolver !importante;

&#x20; }

&#x20; .flex-md-nowrap {

&#x20;   flex-wrap: nowrap !important;

&#x20; }

&#x20; .flex-md-wrap-reverse {

&#x20;   flex-wrap: wrap-reverse !important;

&#x20; }

&#x20; .justify-content-md-start {

&#x20;   justify-content: flex-start !important;

&#x20; }

&#x20; .justify-content-md-end {

&#x20;   justify-content: flex-end !important;

&#x20; }

&#x20; .justify-content-md-center {

&#x20;   justify-content: center !important;

&#x20; }

&#x20; .justify-content-md-between {

&#x20;   justify-content: espaço-entre !important;

&#x20; }

&#x20; .justify-content-md-around {

&#x20;   justify-content: space-around !important;

&#x20; }

&#x20; .justify-content-md-evenly {

&#x20;   justify-content: space-evenly !important;

&#x20; }

&#x20; .align-items-md-start {

&#x20;   align-items: flex-start !important;

&#x20; }

&#x20; .align-items-md-end {

&#x20;   align-items: flex-end !important;

&#x20; }

&#x20; .align-items-md-center {

&#x20;   alinhamento-itens: centralizado !importante;

&#x20; }

&#x20; .align-items-md-baseline {

&#x20;   align-items: baseline !important;

&#x20; }

&#x20; .align-items-md-stretch {

&#x20;   align-items: stretch !important;

&#x20; }

&#x20; .align-content-md-start {

&#x20;   align-content: flex-start !important;

&#x20; }

&#x20; .align-content-md-end {

&#x20;   align-content: flex-end !important;

&#x20; }

&#x20; .align-content-md-center {

&#x20;   alinhamento-conteúdo: centralizado !importante;

&#x20; }

&#x20; .align-content-md-between {

&#x20;   align-content: space-between !important;

&#x20; }

&#x20; .align-content-md-around {

&#x20;   align-content: space-around !important;

&#x20; }

&#x20; .align-content-md-stretch {

&#x20;   align-content: stretch !important;

&#x20; }

&#x20; .align-self-md-auto {

&#x20;   alinhamento-próprio: automático !importante;

&#x20; }

&#x20; .align-self-md-start {

&#x20;   align-self: flex-start !important;

&#x20; }

&#x20; .align-self-md-end {

&#x20;   align-self: flex-end !important;

&#x20; }

&#x20; .align-self-md-center {

&#x20;   alinhamento-próprio: centro !importante;

&#x20; }

&#x20; .align-self-md-baseline {

&#x20;   alinhamento-próprio: linha de base !importante;

&#x20; }

&#x20; .align-self-md-stretch {

&#x20;   alinhamento-próprio: esticar !importante;

&#x20; }

&#x20; .order-md-first {

&#x20;   ordem: -1 !importante;

&#x20; }

&#x20; .order-md-0 {

&#x20;   ordem: 0 !importante;

&#x20; }

&#x20; .order-md-1 {

&#x20;   ordem: 1 !importante;

&#x20; }

&#x20; .order-md-2 {

&#x20;   ordem: 2 !importante;

&#x20; }

&#x20; .order-md-3 {

&#x20;   ordem: 3 !importante;

&#x20; }

&#x20; .order-md-4 {

&#x20;   ordem: 4 !importante;

&#x20; }

&#x20; .order-md-5 {

&#x20;   ordem: 5 !importante;

&#x20; }

&#x20; .order-md-last {

&#x20;   ordem: 6 !importante;

&#x20; }

&#x20; .m-md-0 {

&#x20;   margem: 0 !importante;

&#x20; }

&#x20; .m-md-1 {

&#x20;   margem: 0,25rem !importante;

&#x20; }

&#x20; .m-md-2 {

&#x20;   margem: 0,5rem !importante;

&#x20; }

&#x20; .m-md-3 {

&#x20;   margem: 1rem !importante;

&#x20; }

&#x20; .m-md-4 {

&#x20;   margem: 1,5rem !importante;

&#x20; }

&#x20; .m-md-5 {

&#x20;   margem: 3rem !importante;

&#x20; }

&#x20; .m-md-auto {

&#x20;   margem: automática !importante;

&#x20; }

&#x20; .mx-md-0 {

&#x20;   margem-direita: 0 !importante;

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .mx-md-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .mx-md-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .mx-md-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .mx-md-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .mx-md-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .mx-md-auto {

&#x20;   margem-direita: auto !importante;

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .my-md-0 {

&#x20;   margem-superior: 0 !importante;

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .my-md-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .my-md-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .my-md-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .my-md-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .my-md-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .my-md-auto {

&#x20;   margem-superior: auto !importante;

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .mt-md-0 {

&#x20;   margem-superior: 0 !importante;

&#x20; }

&#x20; .mt-md-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20; }

&#x20; .mt-md-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20; }

&#x20; .mt-md-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20; }

&#x20; .mt-md-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20; }

&#x20; .mt-md-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20; }

&#x20; .mt-md-auto {

&#x20;   margem-superior: auto !importante;

&#x20; }

&#x20; .me-md-0 {

&#x20;   margem-direita: 0 !importante;

&#x20; }

&#x20; .me-md-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20; }

&#x20; .me-md-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20; }

&#x20; .me-md-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20; }

&#x20; .me-md-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20; }

&#x20; .me-md-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20; }

&#x20; .me-md-auto {

&#x20;   margem-direita: auto !importante;

&#x20; }

&#x20; .mb-md-0 {

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .mb-md-1 {

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .mb-md-2 {

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .mb-md-3 {

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .mb-md-4 {

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .mb-md-5 {

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .mb-md-auto {

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .ms-md-0 {

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .ms-md-1 {

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .ms-md-2 {

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .ms-md-3 {

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .ms-md-4 {

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .ms-md-5 {

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .ms-md-auto {

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .p-md-0 {

&#x20;   preenchimento: 0 !importante;

&#x20; }

&#x20; .p-md-1 {

&#x20;   preenchimento: 0,25rem !importante;

&#x20; }

&#x20; .p-md-2 {

&#x20;   preenchimento: 0,5rem !importante;

&#x20; }

&#x20; .p-md-3 {

&#x20;   preenchimento: 1rem !importante;

&#x20; }

&#x20; .p-md-4 {

&#x20;   preenchimento: 1,5rem !importante;

&#x20; }

&#x20; .p-md-5 {

&#x20;   preenchimento: 3rem !importante;

&#x20; }

&#x20; .px-md-0 {

&#x20;   padding-right: 0 !important;

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .px-md-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .px-md-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .px-md-3 {

&#x20;   padding-right: 1rem !important;

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .px-md-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .px-md-5 {

&#x20;   padding-right: 3rem !important;

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .py-md-0 {

&#x20;   padding-top: 0 !important;

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .py-md-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .py-md-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .py-md-3 {

&#x20;   padding-top: 1rem !important;

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .py-md-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .py-md-5 {

&#x20;   padding-top: 3rem !important;

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .pt-md-0 {

&#x20;   padding-top: 0 !important;

&#x20; }

&#x20; .pt-md-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20; }

&#x20; .pt-md-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20; }

&#x20; .pt-md-3 {

&#x20;   padding-top: 1rem !important;

&#x20; }

&#x20; .pt-md-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20; }

&#x20; .pt-md-5 {

&#x20;   padding-top: 3rem !important;

&#x20; }

&#x20; .pe-md-0 {

&#x20;   padding-right: 0 !important;

&#x20; }

&#x20; .pe-md-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20; }

&#x20; .pe-md-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20; }

&#x20; .pe-md-3 {

&#x20;   padding-right: 1rem !important;

&#x20; }

&#x20; .pe-md-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20; }

&#x20; .pe-md-5 {

&#x20;   padding-right: 3rem !important;

&#x20; }

&#x20; .pb-md-0 {

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .pb-md-1 {

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .pb-md-2 {

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .pb-md-3 {

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .pb-md-4 {

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .pb-md-5 {

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .ps-md-0 {

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .ps-md-1 {

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .ps-md-2 {

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .ps-md-3 {

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .ps-md-4 {

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .ps-md-5 {

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .gap-md-0 {

&#x20;   lacuna: 0 !importante;

&#x20; }

&#x20; .gap-md-1 {

&#x20;   espaço: 0,25rem !importante;

&#x20; }

&#x20; .gap-md-2 {

&#x20;   espaço: 0,5rem !importante;

&#x20; }

&#x20; .gap-md-3 {

&#x20;   espaço: 1rem !importante;

&#x20; }

&#x20; .gap-md-4 {

&#x20;   espaço: 1,5rem !importante;

&#x20; }

&#x20; .gap-md-5 {

&#x20;   espaço: 3rem !importante;

&#x20; }

&#x20; .row-gap-md-0 {

&#x20;   espaçamento entre linhas: 0 !importante;

&#x20; }

&#x20; .row-gap-md-1 {

&#x20;   espaçamento entre linhas: 0,25rem !importante;

&#x20; }

&#x20; .row-gap-md-2 {

&#x20;   espaçamento entre linhas: 0,5rem !importante;

&#x20; }

&#x20; .row-gap-md-3 {

&#x20;   espaçamento entre linhas: 1rem !importante;

&#x20; }

&#x20; .row-gap-md-4 {

&#x20;   espaçamento entre linhas: 1,5rem !importante;

&#x20; }

&#x20; .row-gap-md-5 {

&#x20;   espaçamento entre linhas: 3rem !importante;

&#x20; }

&#x20; .column-gap-md-0 {

&#x20;   -moz-column-gap: 0 !important;

&#x20;   espaçamento entre colunas: 0 !importante;

&#x20; }

&#x20; .column-gap-md-1 {

&#x20;   -moz-column-gap: 0.25rem !important;

&#x20;   espaçamento entre colunas: 0,25rem !importante;

&#x20; }

&#x20; .column-gap-md-2 {

&#x20;   -moz-column-gap: 0.5rem !important;

&#x20;   espaçamento entre colunas: 0,5rem !importante;

&#x20; }

&#x20; .column-gap-md-3 {

&#x20;   -moz-column-gap: 1rem !important;

&#x20;   column-gap: 1rem !important;

&#x20; }

&#x20; .column-gap-md-4 {

&#x20;   -moz-column-gap: 1.5rem !important;

&#x20;   espaçamento entre colunas: 1,5rem !importante;

&#x20; }

&#x20; .column-gap-md-5 {

&#x20;   -moz-column-gap: 3rem !important;

&#x20;   column-gap: 3rem !important;

&#x20; }

&#x20; .text-md-start {

&#x20;   alinhamento de texto: esquerda !importante;

&#x20; }

&#x20; .text-md-end {

&#x20;   alinhamento de texto: direita !importante;

&#x20; }

&#x20; .text-md-center {

&#x20;   alinhamento de texto: centralizado !importante;

&#x20; }

}

@media (min-width: 992px) {

&#x20; .float-lg-start {

&#x20;   flutuar: esquerda !importante;

&#x20; }

&#x20; .float-lg-end {

&#x20;   flutuar: direita !importante;

&#x20; }

&#x20; .float-lg-none {

&#x20;   flutuar: nenhum !importante;

&#x20; }

&#x20; .object-fit-lg-contain {

&#x20;   -o-object-fit: contém !importante;

&#x20;   object-fit: conter !important;

&#x20; }

&#x20; .object-fit-lg-cover {

&#x20;   -o-object-fit: cobrir !importante;

&#x20;   object-fit: cobrir !importante;

&#x20; }

&#x20; .object-fit-lg-fill {

&#x20;   -o-object-fit: preencher !importante;

&#x20;   object-fit: preencher !important;

&#x20; }

&#x20; .object-fit-lg-scale {

&#x20;   -o-object-fit: reduzir a escala !importante;

&#x20;   object-fit: reduzir escala !important;

&#x20; }

&#x20; .object-fit-lg-none {

&#x20;   -o-object-fit: nenhum !importante;

&#x20;   object-fit: none !important;

&#x20; }

&#x20; .d-lg-inline {

&#x20;   exibir: embutido !importante;

&#x20; }

&#x20; .d-lg-inline-block {

&#x20;   exibir: inline-block !important;

&#x20; }

&#x20; .d-lg-block {

&#x20;   exibir: bloco !importante;

&#x20; }

&#x20; .d-lg-grid {

&#x20;   exibir: grade !importante;

&#x20; }

&#x20; .d-lg-inline-grid {

&#x20;   exibição: grade em linha !importante;

&#x20; }

&#x20; .d-lg-table {

&#x20;   exibir: tabela !importante;

&#x20; }

&#x20; .d-lg-table-row {

&#x20;   exibir: linha-da-tabela !importante;

&#x20; }

&#x20; .d-lg-table-cell {

&#x20;   exibir: célula-da-tabela !importante;

&#x20; }

&#x20; .d-lg-flex {

&#x20;   exibir: flex !importante;

&#x20; }

&#x20; .d-lg-inline-flex {

&#x20;   exibir: inline-flex !important;

&#x20; }

&#x20; .d-lg-none {

&#x20;   exibir: nenhum !importante;

&#x20; }

&#x20; .flex-lg-fill {

&#x20;   flex: 1 1 auto !importante;

&#x20; }

&#x20; .flex-lg-row {

&#x20;   flex-direction: linha !importante;

&#x20; }

&#x20; .flex-lg-column {

&#x20;   flex-direction: coluna !importante;

&#x20; }

&#x20; .flex-lg-row-reverse {

&#x20;   flex-direction: row-reverse !important;

&#x20; }

&#x20; .flex-lg-column-reverse {

&#x20;   flex-direction: column-reverse !important;

&#x20; }

&#x20; .flex-lg-grow-0 {

&#x20;   flex-grow: 0 !importante;

&#x20; }

&#x20; .flex-lg-grow-1 {

&#x20;   flex-grow: 1 !importante;

&#x20; }

&#x20; .flex-lg-shrink-0 {

&#x20;   flex-shrink: 0 !importante;

&#x20; }

&#x20; .flex-lg-shrink-1 {

&#x20;   flex-shrink: 1 !importante;

&#x20; }

&#x20; .flex-lg-wrap {

&#x20;   flex-wrap: envolver !importante;

&#x20; }

&#x20; .flex-lg-nowrap {

&#x20;   flex-wrap: nowrap !important;

&#x20; }

&#x20; .flex-lg-wrap-reverse {

&#x20;   flex-wrap: wrap-reverse !important;

&#x20; }

&#x20; .justify-content-lg-start {

&#x20;   justify-content: flex-start !important;

&#x20; }

&#x20; .justify-content-lg-end {

&#x20;   justify-content: flex-end !important;

&#x20; }

&#x20; .justify-content-lg-center {

&#x20;   justify-content: center !important;

&#x20; }

&#x20; .justify-content-lg-between {

&#x20;   justify-content: espaço-entre !important;

&#x20; }

&#x20; .justify-content-lg-around {

&#x20;   justify-content: space-around !important;

&#x20; }

&#x20; .justify-content-lg-evenly {

&#x20;   justify-content: space-evenly !important;

&#x20; }

&#x20; .align-items-lg-start {

&#x20;   align-items: flex-start !important;

&#x20; }

&#x20; .align-items-lg-end {

&#x20;   align-items: flex-end !important;

&#x20; }

&#x20; .align-items-lg-center {

&#x20;   alinhamento-itens: centralizado !importante;

&#x20; }

&#x20; .align-items-lg-baseline {

&#x20;   align-items: baseline !important;

&#x20; }

&#x20; .align-items-lg-stretch {

&#x20;   align-items: stretch !important;

&#x20; }

&#x20; .align-content-lg-start {

&#x20;   align-content: flex-start !important;

&#x20; }

&#x20; .align-content-lg-end {

&#x20;   align-content: flex-end !important;

&#x20; }

&#x20; .align-content-lg-center {

&#x20;   alinhamento-conteúdo: centralizado !importante;

&#x20; }

&#x20; .align-content-lg-between {

&#x20;   align-content: space-between !important;

&#x20; }

&#x20; .align-content-lg-around {

&#x20;   align-content: space-around !important;

&#x20; }

&#x20; .align-content-lg-stretch {

&#x20;   align-content: stretch !important;

&#x20; }

&#x20; .align-self-lg-auto {

&#x20;   alinhamento-próprio: automático !importante;

&#x20; }

&#x20; .align-self-lg-start {

&#x20;   align-self: flex-start !important;

&#x20; }

&#x20; .align-self-lg-end {

&#x20;   align-self: flex-end !important;

&#x20; }

&#x20; .align-self-lg-center {

&#x20;   alinhamento-próprio: centro !importante;

&#x20; }

&#x20; .align-self-lg-baseline {

&#x20;   alinhamento-próprio: linha de base !importante;

&#x20; }

&#x20; .align-self-lg-stretch {

&#x20;   alinhamento-próprio: esticar !importante;

&#x20; }

&#x20; .order-lg-first {

&#x20;   ordem: -1 !importante;

&#x20; }

&#x20; .order-lg-0 {

&#x20;   ordem: 0 !importante;

&#x20; }

&#x20; .order-lg-1 {

&#x20;   ordem: 1 !importante;

&#x20; }

&#x20; .order-lg-2 {

&#x20;   ordem: 2 !importante;

&#x20; }

&#x20; .order-lg-3 {

&#x20;   ordem: 3 !importante;

&#x20; }

&#x20; .order-lg-4 {

&#x20;   ordem: 4 !importante;

&#x20; }

&#x20; .order-lg-5 {

&#x20;   ordem: 5 !importante;

&#x20; }

&#x20; .order-lg-last {

&#x20;   ordem: 6 !importante;

&#x20; }

&#x20; .m-lg-0 {

&#x20;   margem: 0 !importante;

&#x20; }

&#x20; .m-lg-1 {

&#x20;   margem: 0,25rem !importante;

&#x20; }

&#x20; .m-lg-2 {

&#x20;   margem: 0,5rem !importante;

&#x20; }

&#x20; .m-lg-3 {

&#x20;   margem: 1rem !importante;

&#x20; }

&#x20; .m-lg-4 {

&#x20;   margem: 1,5rem !importante;

&#x20; }

&#x20; .m-lg-5 {

&#x20;   margem: 3rem !importante;

&#x20; }

&#x20; .m-lg-auto {

&#x20;   margem: automática !importante;

&#x20; }

&#x20; .mx-lg-0 {

&#x20;   margem-direita: 0 !importante;

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .mx-lg-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .mx-lg-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .mx-lg-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .mx-lg-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .mx-lg-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .mx-lg-auto {

&#x20;   margem-direita: auto !importante;

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .my-lg-0 {

&#x20;   margem-superior: 0 !importante;

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .my-lg-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .my-lg-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .my-lg-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .my-lg-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .my-lg-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .my-lg-auto {

&#x20;   margem-superior: auto !importante;

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .mt-lg-0 {

&#x20;   margem-superior: 0 !importante;

&#x20; }

&#x20; .mt-lg-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20; }

&#x20; .mt-lg-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20; }

&#x20; .mt-lg-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20; }

&#x20; .mt-lg-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20; }

&#x20; .mt-lg-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20; }

&#x20; .mt-lg-auto {

&#x20;   margem-superior: auto !importante;

&#x20; }

&#x20; .me-lg-0 {

&#x20;   margem-direita: 0 !importante;

&#x20; }

&#x20; .me-lg-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20; }

&#x20; .me-lg-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20; }

&#x20; .me-lg-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20; }

&#x20; .me-lg-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20; }

&#x20; .me-lg-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20; }

&#x20; .me-lg-auto {

&#x20;   margem-direita: auto !importante;

&#x20; }

&#x20; .mb-lg-0 {

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .mb-lg-1 {

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .mb-lg-2 {

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .mb-lg-3 {

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .mb-lg-4 {

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .mb-lg-5 {

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .mb-lg-auto {

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .ms-lg-0 {

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .ms-lg-1 {

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .ms-lg-2 {

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .ms-lg-3 {

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .ms-lg-4 {

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .ms-lg-5 {

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .ms-lg-auto {

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .p-lg-0 {

&#x20;   preenchimento: 0 !importante;

&#x20; }

&#x20; .p-lg-1 {

&#x20;   preenchimento: 0,25rem !importante;

&#x20; }

&#x20; .p-lg-2 {

&#x20;   preenchimento: 0,5rem !importante;

&#x20; }

&#x20; .p-lg-3 {

&#x20;   preenchimento: 1rem !importante;

&#x20; }

&#x20; .p-lg-4 {

&#x20;   preenchimento: 1,5rem !importante;

&#x20; }

&#x20; .p-lg-5 {

&#x20;   preenchimento: 3rem !importante;

&#x20; }

&#x20; .px-lg-0 {

&#x20;   padding-right: 0 !important;

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .px-lg-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .px-lg-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .px-lg-3 {

&#x20;   padding-right: 1rem !important;

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .px-lg-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .px-lg-5 {

&#x20;   padding-right: 3rem !important;

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .py-lg-0 {

&#x20;   padding-top: 0 !important;

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .py-lg-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .py-lg-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .py-lg-3 {

&#x20;   padding-top: 1rem !important;

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .py-lg-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .py-lg-5 {

&#x20;   padding-top: 3rem !important;

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .pt-lg-0 {

&#x20;   padding-top: 0 !important;

&#x20; }

&#x20; .pt-lg-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20; }

&#x20; .pt-lg-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20; }

&#x20; .pt-lg-3 {

&#x20;   padding-top: 1rem !important;

&#x20; }

&#x20; .pt-lg-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20; }

&#x20; .pt-lg-5 {

&#x20;   padding-top: 3rem !important;

&#x20; }

&#x20; .pe-lg-0 {

&#x20;   padding-right: 0 !important;

&#x20; }

&#x20; .pe-lg-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20; }

&#x20; .pe-lg-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20; }

&#x20; .pe-lg-3 {

&#x20;   padding-right: 1rem !important;

&#x20; }

&#x20; .pe-lg-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20; }

&#x20; .pe-lg-5 {

&#x20;   padding-right: 3rem !important;

&#x20; }

&#x20; .pb-lg-0 {

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .pb-lg-1 {

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .pb-lg-2 {

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .pb-lg-3 {

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .pb-lg-4 {

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .pb-lg-5 {

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .ps-lg-0 {

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .ps-lg-1 {

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .ps-lg-2 {

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .ps-lg-3 {

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .ps-lg-4 {

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .ps-lg-5 {

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .gap-lg-0 {

&#x20;   lacuna: 0 !importante;

&#x20; }

&#x20; .gap-lg-1 {

&#x20;   espaço: 0,25rem !importante;

&#x20; }

&#x20; .gap-lg-2 {

&#x20;   espaço: 0,5rem !importante;

&#x20; }

&#x20; .gap-lg-3 {

&#x20;   espaço: 1rem !importante;

&#x20; }

&#x20; .gap-lg-4 {

&#x20;   espaço: 1,5rem !importante;

&#x20; }

&#x20; .gap-lg-5 {

&#x20;   espaço: 3rem !importante;

&#x20; }

&#x20; .row-gap-lg-0 {

&#x20;   espaçamento entre linhas: 0 !importante;

&#x20; }

&#x20; .row-gap-lg-1 {

&#x20;   espaçamento entre linhas: 0,25rem !importante;

&#x20; }

&#x20; .row-gap-lg-2 {

&#x20;   espaçamento entre linhas: 0,5rem !importante;

&#x20; }

&#x20; .row-gap-lg-3 {

&#x20;   espaçamento entre linhas: 1rem !importante;

&#x20; }

&#x20; .row-gap-lg-4 {

&#x20;   espaçamento entre linhas: 1,5rem !importante;

&#x20; }

&#x20; .row-gap-lg-5 {

&#x20;   espaçamento entre linhas: 3rem !importante;

&#x20; }

&#x20; .column-gap-lg-0 {

&#x20;   -moz-column-gap: 0 !important;

&#x20;   espaçamento entre colunas: 0 !importante;

&#x20; }

&#x20; .column-gap-lg-1 {

&#x20;   -moz-column-gap: 0.25rem !important;

&#x20;   espaçamento entre colunas: 0,25rem !importante;

&#x20; }

&#x20; .column-gap-lg-2 {

&#x20;   -moz-column-gap: 0.5rem !important;

&#x20;   espaçamento entre colunas: 0,5rem !importante;

&#x20; }

&#x20; .column-gap-lg-3 {

&#x20;   -moz-column-gap: 1rem !important;

&#x20;   column-gap: 1rem !important;

&#x20; }

&#x20; .column-gap-lg-4 {

&#x20;   -moz-column-gap: 1.5rem !important;

&#x20;   espaçamento entre colunas: 1,5rem !importante;

&#x20; }

&#x20; .column-gap-lg-5 {

&#x20;   -moz-column-gap: 3rem !important;

&#x20;   column-gap: 3rem !important;

&#x20; }

&#x20; .text-lg-start {

&#x20;   alinhamento de texto: esquerda !importante;

&#x20; }

&#x20; .text-lg-end {

&#x20;   alinhamento de texto: direita !importante;

&#x20; }

&#x20; .text-lg-center {

&#x20;   alinhamento de texto: centralizado !importante;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .float-xl-start {

&#x20;   flutuar: esquerda !importante;

&#x20; }

&#x20; .float-xl-end {

&#x20;   flutuar: direita !importante;

&#x20; }

&#x20; .float-xl-none {

&#x20;   flutuar: nenhum !importante;

&#x20; }

&#x20; .object-fit-xl-contain {

&#x20;   -o-object-fit: contém !importante;

&#x20;   object-fit: conter !important;

&#x20; }

&#x20; .object-fit-xl-cover {

&#x20;   -o-object-fit: cobrir !importante;

&#x20;   object-fit: cobrir !importante;

&#x20; }

&#x20; .object-fit-xl-fill {

&#x20;   -o-object-fit: preencher !importante;

&#x20;   object-fit: preencher !important;

&#x20; }

&#x20; .object-fit-xl-scale {

&#x20;   -o-object-fit: reduzir a escala !importante;

&#x20;   object-fit: reduzir escala !important;

&#x20; }

&#x20; .object-fit-xl-none {

&#x20;   -o-object-fit: nenhum !importante;

&#x20;   object-fit: none !important;

&#x20; }

&#x20; .d-xl-inline {

&#x20;   exibir: embutido !importante;

&#x20; }

&#x20; .d-xl-inline-block {

&#x20;   exibir: inline-block !important;

&#x20; }

&#x20; .d-xl-block {

&#x20;   exibir: bloco !importante;

&#x20; }

&#x20; .d-xl-grid {

&#x20;   exibir: grade !importante;

&#x20; }

&#x20; .d-xl-inline-grid {

&#x20;   exibição: grade em linha !importante;

&#x20; }

&#x20; .d-xl-table {

&#x20;   exibir: tabela !importante;

&#x20; }

&#x20; .d-xl-table-row {

&#x20;   exibir: linha-da-tabela !importante;

&#x20; }

&#x20; .d-xl-table-cell {

&#x20;   exibir: célula-da-tabela !importante;

&#x20; }

&#x20; .d-xl-flex {

&#x20;   exibir: flex !importante;

&#x20; }

&#x20; .d-xl-inline-flex {

&#x20;   exibir: inline-flex !important;

&#x20; }

&#x20; .d-xl-nenhum {

&#x20;   exibir: nenhum !importante;

&#x20; }

&#x20; .flex-xl-fill {

&#x20;   flex: 1 1 auto !importante;

&#x20; }

&#x20; .flex-xl-row {

&#x20;   flex-direction: linha !importante;

&#x20; }

&#x20; .flex-xl-column {

&#x20;   flex-direction: coluna !importante;

&#x20; }

&#x20; .flex-xl-row-reverse {

&#x20;   flex-direction: row-reverse !important;

&#x20; }

&#x20; .flex-xl-column-reverse {

&#x20;   flex-direction: column-reverse !important;

&#x20; }

&#x20; .flex-xl-grow-0 {

&#x20;   flex-grow: 0 !importante;

&#x20; }

&#x20; .flex-xl-grow-1 {

&#x20;   flex-grow: 1 !importante;

&#x20; }

&#x20; .flex-xl-shrink-0 {

&#x20;   flex-shrink: 0 !importante;

&#x20; }

&#x20; .flex-xl-shrink-1 {

&#x20;   flex-shrink: 1 !importante;

&#x20; }

&#x20; .flex-xl-wrap {

&#x20;   flex-wrap: envolver !importante;

&#x20; }

&#x20; .flex-xl-nowrap {

&#x20;   flex-wrap: nowrap !important;

&#x20; }

&#x20; .flex-xl-wrap-reverse {

&#x20;   flex-wrap: wrap-reverse !important;

&#x20; }

&#x20; .justify-content-xl-start {

&#x20;   justify-content: flex-start !important;

&#x20; }

&#x20; .justify-content-xl-end {

&#x20;   justify-content: flex-end !important;

&#x20; }

&#x20; .justify-content-xl-center {

&#x20;   justify-content: center !important;

&#x20; }

&#x20; .justify-content-xl-between {

&#x20;   justify-content: espaço-entre !important;

&#x20; }

&#x20; .justify-content-xl-around {

&#x20;   justify-content: space-around !important;

&#x20; }

&#x20; .justify-content-xl-evenly {

&#x20;   justify-content: space-evenly !important;

&#x20; }

&#x20; .align-items-xl-start {

&#x20;   align-items: flex-start !important;

&#x20; }

&#x20; .align-items-xl-end {

&#x20;   align-items: flex-end !important;

&#x20; }

&#x20; .align-items-xl-center {

&#x20;   alinhamento-itens: centralizado !importante;

&#x20; }

&#x20; .align-items-xl-baseline {

&#x20;   align-items: baseline !important;

&#x20; }

&#x20; .align-items-xl-stretch {

&#x20;   align-items: stretch !important;

&#x20; }

&#x20; .align-content-xl-start {

&#x20;   align-content: flex-start !important;

&#x20; }

&#x20; .align-content-xl-end {

&#x20;   align-content: flex-end !important;

&#x20; }

&#x20; .align-content-xl-center {

&#x20;   alinhamento-conteúdo: centralizado !importante;

&#x20; }

&#x20; .align-content-xl-between {

&#x20;   align-content: space-between !important;

&#x20; }

&#x20; .align-content-xl-around {

&#x20;   align-content: space-around !important;

&#x20; }

&#x20; .align-content-xl-stretch {

&#x20;   align-content: stretch !important;

&#x20; }

&#x20; .align-self-xl-auto {

&#x20;   alinhamento-próprio: automático !importante;

&#x20; }

&#x20; .align-self-xl-start {

&#x20;   align-self: flex-start !important;

&#x20; }

&#x20; .align-self-xl-end {

&#x20;   align-self: flex-end !important;

&#x20; }

&#x20; .align-self-xl-center {

&#x20;   alinhamento-próprio: centro !importante;

&#x20; }

&#x20; .align-self-xl-baseline {

&#x20;   alinhamento-próprio: linha de base !importante;

&#x20; }

&#x20; .align-self-xl-stretch {

&#x20;   alinhamento-próprio: esticar !importante;

&#x20; }

&#x20; .order-xl-first {

&#x20;   ordem: -1 !importante;

&#x20; }

&#x20; .order-xl-0 {

&#x20;   ordem: 0 !importante;

&#x20; }

&#x20; .order-xl-1 {

&#x20;   ordem: 1 !importante;

&#x20; }

&#x20; .order-xl-2 {

&#x20;   ordem: 2 !importante;

&#x20; }

&#x20; .order-xl-3 {

&#x20;   ordem: 3 !importante;

&#x20; }

&#x20; .order-xl-4 {

&#x20;   ordem: 4 !importante;

&#x20; }

&#x20; .order-xl-5 {

&#x20;   ordem: 5 !importante;

&#x20; }

&#x20; .order-xl-last {

&#x20;   ordem: 6 !importante;

&#x20; }

&#x20; .m-xl-0 {

&#x20;   margem: 0 !importante;

&#x20; }

&#x20; .m-xl-1 {

&#x20;   margem: 0,25rem !importante;

&#x20; }

&#x20; .m-xl-2 {

&#x20;   margem: 0,5rem !importante;

&#x20; }

&#x20; .m-xl-3 {

&#x20;   margem: 1rem !importante;

&#x20; }

&#x20; .m-xl-4 {

&#x20;   margem: 1,5rem !importante;

&#x20; }

&#x20; .m-xl-5 {

&#x20;   margem: 3rem !importante;

&#x20; }

&#x20; .m-xl-auto {

&#x20;   margem: automática !importante;

&#x20; }

&#x20; .mx-xl-0 {

&#x20;   margem-direita: 0 !importante;

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .mx-xl-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20;   margem n-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .mx-xl-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .mx-xl-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .mx-xl-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .mx-xl-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .mx-xl-auto {

&#x20;   margem-direita: auto !importante;

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .my-xl-0 {

&#x20;   margem-superior: 0 !importante;

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .my-xl-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .my-xl-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .my-xl-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .my-xl-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .my-xl-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .my-xl-auto {

&#x20;   margem-superior: auto !importante;

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .mt-xl-0 {

&#x20;   margem-superior: 0 !importante;

&#x20; }

&#x20; .mt-xl-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20; }

&#x20; .mt-xl-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20; }

&#x20; .mt-xl-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20; }

&#x20; .mt-xl-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20; }

&#x20; .mt-xl-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20; }

&#x20; .mt-xl-auto {

&#x20;   margem-superior: auto !importante;

&#x20; }

&#x20; .me-xl-0 {

&#x20;   margem-direita: 0 !importante;

&#x20; }

&#x20; .me-xl-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20; }

&#x20; .me-xl-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20; }

&#x20; .me-xl-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20; }

&#x20; .me-xl-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20; }

&#x20; .me-xl-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20; }

&#x20; .me-xl-auto {

&#x20;   margem-direita: auto !importante;

&#x20; }

&#x20; .mb-xl-0 {

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .mb-xl-1 {

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .mb-xl-2 {

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .mb-xl-3 {

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .mb-xl-4 {

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .mb-xl-5 {

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .mb-xl-auto {

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .ms-xl-0 {

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .ms-xl-1 {

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .ms-xl-2 {

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .ms-xl-3 {

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .ms-xl-4 {

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .ms-xl-5 {

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .ms-xl-auto {

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .p-xl-0 {

&#x20;   preenchimento: 0 !importante;

&#x20; }

&#x20; .p-xl-1 {

&#x20;   preenchimento: 0,25rem !importante;

&#x20; }

&#x20; .p-xl-2 {

&#x20;   preenchimento: 0,5rem !importante;

&#x20; }

&#x20; .p-xl-3 {

&#x20;   preenchimento: 1rem !importante;

&#x20; }

&#x20; .p-xl-4 {

&#x20;   preenchimento: 1,5rem !importante;

&#x20; }

&#x20; .p-xl-5 {

&#x20;   preenchimento: 3rem !importante;

&#x20; }

&#x20; .px-xl-0 {

&#x20;   padding-right: 0 !important;

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .px-xl-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .px-xl-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .px-xl-3 {

&#x20;   padding-right: 1rem !important;

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .px-xl-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .px-xl-5 {

&#x20;   padding-right: 3rem !important;

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .py-xl-0 {

&#x20;   padding-top: 0 !important;

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .py-xl-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .py-xl-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .py-xl-3 {

&#x20;   padding-top: 1rem !important;

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .py-xl-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .py-xl-5 {

&#x20;   padding-top: 3rem !important;

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .pt-xl-0 {

&#x20;   padding-top: 0 !important;

&#x20; }

&#x20; .pt-xl-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20; }

&#x20; .pt-xl-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20; }

&#x20; .pt-xl-3 {

&#x20;   padding-top: 1rem !important;

&#x20; }

&#x20; .pt-xl-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20; }

&#x20; .pt-xl-5 {

&#x20;   padding-top: 3rem !important;

&#x20; }

&#x20; .pe-xl-0 {

&#x20;   padding-right: 0 !important;

&#x20; }

&#x20; .pe-xl-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20; }

&#x20; .pe-xl-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20; }

&#x20; .pe-xl-3 {

&#x20;   padding-right: 1rem !important;

&#x20; }

&#x20; .pe-xl-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20; }

&#x20; .pe-xl-5 {

&#x20;   padding-right: 3rem !important;

&#x20; }

&#x20; .pb-xl-0 {

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .pb-xl-1 {

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .pb-xl-2 {

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .pb-xl-3 {

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .pb-xl-4 {

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .pb-xl-5 {

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .ps-xl-0 {

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .ps-xl-1 {

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .ps-xl-2 {

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .ps-xl-3 {

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .ps-xl-4 {

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .ps-xl-5 {

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .gap-xl-0 {

&#x20;   lacuna: 0 !importante;

&#x20; }

&#x20; .gap-xl-1 {

&#x20;   espaço: 0,25rem !importante;

&#x20; }

&#x20; .gap-xl-2 {

&#x20;   espaço: 0,5rem !importante;

&#x20; }

&#x20; .gap-xl-3 {

&#x20;   espaço: 1rem !importante;

&#x20; }

&#x20; .gap-xl-4 {

&#x20;   espaço: 1,5rem !importante;

&#x20; }

&#x20; .gap-xl-5 {

&#x20;   espaço: 3rem !importante;

&#x20; }

&#x20; .row-gap-xl-0 {

&#x20;   espaçamento entre linhas: 0 !importante;

&#x20; }

&#x20; .row-gap-xl-1 {

&#x20;   espaçamento entre linhas: 0,25rem !importante;

&#x20; }

&#x20; .row-gap-xl-2 {

&#x20;   espaçamento entre linhas: 0,5rem !importante;

&#x20; }

&#x20; .row-gap-xl-3 {

&#x20;   espaçamento entre linhas: 1rem !importante;

&#x20; }

&#x20; .row-gap-xl-4 {

&#x20;   espaçamento entre linhas: 1,5rem !importante;

&#x20; }

&#x20; .row-gap-xl-5 {

&#x20;   espaçamento entre linhas: 3rem !importante;

&#x20; }

&#x20; .column-gap-xl-0 {

&#x20;   -moz-column-gap: 0 !important;

&#x20;   espaçamento entre colunas: 0 !importante;

&#x20; }

&#x20; .column-gap-xl-1 {

&#x20;   -moz-column-gap: 0.25rem !important;

&#x20;   espaçamento entre colunas: 0,25rem !importante;

&#x20; }

&#x20; .column-gap-xl-2 {

&#x20;   -moz-column-gap: 0.5rem !important;

&#x20;   espaçamento entre colunas: 0,5rem !importante;

&#x20; }

&#x20; .column-gap-xl-3 {

&#x20;   -moz-column-gap: 1rem !important;

&#x20;   column-gap: 1rem !important;

&#x20; }

&#x20; .column-gap-xl-4 {

&#x20;   -moz-column-gap: 1.5rem !important;

&#x20;   espaçamento entre colunas: 1,5rem !importante;

&#x20; }

&#x20; .column-gap-xl-5 {

&#x20;   -moz-column-gap: 3rem !important;

&#x20;   column-gap: 3rem !important;

&#x20; }

&#x20; .text-xl-start {

&#x20;   alinhamento de texto: esquerda !importante;

&#x20; }

&#x20; .text-xl-end {

&#x20;   alinhamento de texto: direita !importante;

&#x20; }

&#x20; .text-xl-center {

&#x20;   alinhamento de texto: centralizado !importante;

&#x20; }

}

@media (min-width: 1400px) {

&#x20; .float-xxl-start {

&#x20;   flutuar: esquerda !importante;

&#x20; }

&#x20; .float-xxl-end {

&#x20;   flutuar: direita !importante;

&#x20; }

&#x20; .float-xxl-none {

&#x20;   flutuar: nenhum !importante;

&#x20; }

&#x20; .object-fit-xxl-contain {

&#x20;   -o-object-fit: contém !importante;

&#x20;   object-fit: conter !important;

&#x20; }

&#x20; .object-fit-xxl-cover {

&#x20;   -o-object-fit: cobrir !importante;

&#x20;   object-fit: cobrir !importante;

&#x20; }

&#x20; .object-fit-xxl-fill {

&#x20;   -o-object-fit: preencher !importante;

&#x20;   object-fit: preencher !important;

&#x20; }

&#x20; .object-fit-xxl-scale {

&#x20;   -o-object-fit: reduzir a escala !importante;

&#x20;   object-fit: reduzir escala !important;

&#x20; }

&#x20; .object-fit-xxl-none {

&#x20;   -o-object-fit: nenhum !importante;

&#x20;   object-fit: none !important;

&#x20; }

&#x20; .d-xxl-inline {

&#x20;   exibir: embutido !importante;

&#x20; }

&#x20; .d-xxl-inline-block {

&#x20;   exibir: inline-block !important;

&#x20; }

&#x20; .d-xxl-block {

&#x20;   exibir: bloco !importante;

&#x20; }

&#x20; .d-xxl-grid {

&#x20;   exibir: grade !importante;

&#x20; }

&#x20; .d-xxl-inline-grid {

&#x20;   exibição: grade em linha !importante;

&#x20; }

&#x20; .d-xxl-table {

&#x20;   exibir: tabela !importante;

&#x20; }

&#x20; .d-xxl-table-row {

&#x20;   exibir: linha-da-tabela !importante;

&#x20; }

&#x20; .d-xxl-table-cell {

&#x20;   exibir: célula-da-tabela !importante;

&#x20; }

&#x20; .d-xxl-flex {

&#x20;   exibir: flex !importante;

&#x20; }

&#x20; .d-xxl-inline-flex {

&#x20;   exibir: inline-flex !important;

&#x20; }

&#x20; .d-xxl-nenhum {

&#x20;   exibir: nenhum !importante;

&#x20; }

&#x20; .flex-xxl-fill {

&#x20;   flex: 1 1 auto !importante;

&#x20; }

&#x20; .flex-xxl-row {

&#x20;   flex-direction: linha !importante;

&#x20; }

&#x20; .flex-xxl-column {

&#x20;   flex-direction: coluna !importante;

&#x20; }

&#x20; .flex-xxl-row-reverse {

&#x20;   flex-direction: row-reverse !important;

&#x20; }

&#x20; .flex-xxl-column-reverse {

&#x20;   flex-direction: column-reverse !important;

&#x20; }

&#x20; .flex-xxl-grow-0 {

&#x20;   flex-grow: 0 !importante;

&#x20; }

&#x20; .flex-xxl-grow-1 {

&#x20;   flex-grow: 1 !importante;

&#x20; }

&#x20; .flex-xxl-shrink-0 {

&#x20;   flex-shrink: 0 !importante;

&#x20; }

&#x20; .flex-xxl-shrink-1 {

&#x20;   flex-shrink: 1 !importante;

&#x20; }

&#x20; .flex-xxl-wrap {

&#x20;   flex-wrap: envolver !importante;

&#x20; }

&#x20; .flex-xxl-nowrap {

&#x20;   flex-wrap: nowrap !important;

&#x20; }

&#x20; .flex-xxl-wrap-reverse {

&#x20;   flex-wrap: wrap-reverse !important;

&#x20; }

&#x20; .justify-content-xxl-start {

&#x20;   justify-content: flex-start !important;

&#x20; }

&#x20; .justify-content-xxl-end {

&#x20;   justify-content: flex-end !important;

&#x20; }

&#x20; .justify-content-xxl-center {

&#x20;   justify-content: center !important;

&#x20; }

&#x20; .justify-content-xxl-between {

&#x20;   justify-content: espaço-entre !important;

&#x20; }

&#x20; .justify-content-xxl-around {

&#x20;   justify-content: space-around !important;

&#x20; }

&#x20; .justify-content-xxl-evenly {

&#x20;   justify-content: space-evenly !important;

&#x20; }

&#x20; .align-items-xxl-start {

&#x20;   align-items: flex-start !important;

&#x20; }

&#x20; .align-items-xxl-end {

&#x20;   align-items: flex-end !important;

&#x20; }

&#x20; .align-items-xxl-center {

&#x20;   alinhamento-itens: centralizado !importante;

&#x20; }

&#x20; .align-items-xxl-baseline {

&#x20;   align-items: baseline !important;

&#x20; }

&#x20; .align-items-xxl-stretch {

&#x20;   align-items: stretch !important;

&#x20; }

&#x20; .align-content-xxl-start {

&#x20;   align-content: flex-start !important;

&#x20; }

&#x20; .align-content-xxl-end {

&#x20;   align-content: flex-end !important;

&#x20; }

&#x20; .align-content-xxl-center {

&#x20;   alinhamento-conteúdo: centralizado !importante;

&#x20; }

&#x20; .align-content-xxl-between {

&#x20;   align-content: space-between !important;

&#x20; }

&#x20; .align-content-xxl-around {

&#x20;   align-content: space-around !important;

&#x20; }

&#x20; .align-content-xxl-stretch {

&#x20;   align-content: stretch !important;

&#x20; }

&#x20; .align-self-xxl-auto {

&#x20;   alinhamento-próprio: automático !importante;

&#x20; }

&#x20; .align-self-xxl-start {

&#x20;   align-self: flex-start !important;

&#x20; }

&#x20; .align-self-xxl-end {

&#x20;   align-self: flex-end !important;

&#x20; }

&#x20; .align-self-xxl-center {

&#x20;   alinhamento-próprio: centro !importante;

&#x20; }

&#x20; .align-self-xxl-baseline {

&#x20;   alinhamento-próprio: linha de base !importante;

&#x20; }

&#x20; .align-self-xxl-stretch {

&#x20;   alinhamento-próprio: esticar !importante;

&#x20; }

&#x20; .order-xxl-first {

&#x20;   ordem: -1 !importante;

&#x20; }

&#x20; .order-xxl-0 {

&#x20;   ordem: 0 !importante;

&#x20; }

&#x20; .order-xxl-1 {

&#x20;   ordem: 1 !importante;

&#x20; }

&#x20; .order-xxl-2 {

&#x20;   ordem: 2 !importante;

&#x20; }

&#x20; .order-xxl-3 {

&#x20;   ordem: 3 !importante;

&#x20; }

&#x20; .order-xxl-4 {

&#x20;   ordem: 4 !importante;

&#x20; }

&#x20; .order-xxl-5 {

&#x20;   ordem: 5 !importante;

&#x20; }

&#x20; .order-xxl-last {

&#x20;   ordem: 6 !importante;

&#x20; }

&#x20; .m-xxl-0 {

&#x20;   margem: 0 !importante;

&#x20; }

&#x20; .m-xxl-1 {

&#x20;   margem: 0,25rem !importante;

&#x20; }

&#x20; .m-xxl-2 {

&#x20;   margem: 0,5rem !importante;

&#x20; }

&#x20; .m-xxl-3 {

&#x20;   margem: 1rem !importante;

&#x20; }

&#x20; .m-xxl-4 {

&#x20;   margem: 1,5rem !importante;

&#x20; }

&#x20; .m-xxl-5 {

&#x20;   margem: 3rem !importante;

&#x20; }

&#x20; .m-xxl-auto {

&#x20;   margem: automática !importante;

&#x20; }

&#x20; .mx-xxl-0 {

&#x20;   margem-direita: 0 !importante;

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .mx-xxl-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .mx-xxl-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .mx-xxl-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .mx-xxl-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .mx-xxl-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .mx-xxl-auto {

&#x20;   margem-direita: auto !importante;

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .my-xxl-0 {

&#x20;   margem-superior: 0 !importante;

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .my-xxl-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .my-xxl-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .my-xxl-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .my-xxl-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .my-xxl-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .meu-auto-xxl {

&#x20;   margem-superior: auto !importante;

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .mt-xxl-0 {

&#x20;   margem-superior: 0 !importante;

&#x20; }

&#x20; .mt-xxl-1 {

&#x20;   margem-superior: 0,25rem !importante;

&#x20; }

&#x20; .mt-xxl-2 {

&#x20;   margem-superior: 0,5rem !importante;

&#x20; }

&#x20; .mt-xxl-3 {

&#x20;   margem-superior: 1rem !importante;

&#x20; }

&#x20; .mt-xxl-4 {

&#x20;   margem-superior: 1,5rem !importante;

&#x20; }

&#x20; .mt-xxl-5 {

&#x20;   margem-superior: 3rem !importante;

&#x20; }

&#x20; .mt-xxl-auto {

&#x20;   margem-superior: auto !importante;

&#x20; }

&#x20; .me-xxl-0 {

&#x20;   margem-direita: 0 !importante;

&#x20; }

&#x20; .me-xxl-1 {

&#x20;   margem-direita: 0,25rem !importante;

&#x20; }

&#x20; .me-xxl-2 {

&#x20;   margem-direita: 0,5rem !importante;

&#x20; }

&#x20; .me-xxl-3 {

&#x20;   margem-direita: 1rem !importante;

&#x20; }

&#x20; .me-xxl-4 {

&#x20;   margem-direita: 1,5rem !importante;

&#x20; }

&#x20; .me-xxl-5 {

&#x20;   margem-direita: 3rem !importante;

&#x20; }

&#x20; .me-xxl-auto {

&#x20;   margem-direita: auto !importante;

&#x20; }

&#x20; .mb-xxl-0 {

&#x20;   margem-inferior: 0 !importante;

&#x20; }

&#x20; .mb-xxl-1 {

&#x20;   margem-inferior: 0,25rem !importante;

&#x20; }

&#x20; .mb-xxl-2 {

&#x20;   margem-inferior: 0,5rem !importante;

&#x20; }

&#x20; .mb-xxl-3 {

&#x20;   margem-inferior: 1rem !importante;

&#x20; }

&#x20; .mb-xxl-4 {

&#x20;   margem-inferior: 1,5rem !importante;

&#x20; }

&#x20; .mb-xxl-5 {

&#x20;   margem-inferior: 3rem !importante;

&#x20; }

&#x20; .mb-xxl-auto {

&#x20;   margem-inferior: auto !importante;

&#x20; }

&#x20; .ms-xxl-0 {

&#x20;   margem-esquerda: 0 !importante;

&#x20; }

&#x20; .ms-xxl-1 {

&#x20;   margem-esquerda: 0,25rem !importante;

&#x20; }

&#x20; .ms-xxl-2 {

&#x20;   margem-esquerda: 0,5rem !importante;

&#x20; }

&#x20; .ms-xxl-3 {

&#x20;   margem-esquerda: 1rem !importante;

&#x20; }

&#x20; .ms-xxl-4 {

&#x20;   margem-esquerda: 1,5rem !importante;

&#x20; }

&#x20; .ms-xxl-5 {

&#x20;   margem-esquerda: 3rem !importante;

&#x20; }

&#x20; .ms-xxl-auto {

&#x20;   margem-esquerda: auto !importante;

&#x20; }

&#x20; .p-xxl-0 {

&#x20;   preenchimento: 0 !importante;

&#x20; }

&#x20; .p-xxl-1 {

&#x20;   preenchimento: 0,25rem !importante;

&#x20; }

&#x20; .p-xxl-2 {

&#x20;   preenchimento: 0,5rem !importante;

&#x20; }

&#x20; .p-xxl-3 {

&#x20;   preenchimento: 1rem !importante;

&#x20; }

&#x20; .p-xxl-4 {

&#x20;   preenchimento: 1,5rem !importante;

&#x20; }

&#x20; .p-xxl-5 {

&#x20;   preenchimento: 3rem !importante;

&#x20; }

&#x20; .px-xxl-0 {

&#x20;   padding-right: 0 !important;

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .px-xxl-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .px-xxl-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .px-xxl-3 {

&#x20;   padding-right: 1rem !important;

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .px-xxl-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .px-xxl-5 {

&#x20;   padding-right: 3rem !important;

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .py-xxl-0 {

&#x20;   padding-top: 0 !important;

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .py-xxl-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .py-xxl-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .py-xxl-3 {

&#x20;   padding-top: 1rem !important;

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .py-xxl-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .py-xxl-5 {

&#x20;   padding-top: 3rem !important;

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .pt-xxl-0 {

&#x20;   padding-top: 0 !important;

&#x20; }

&#x20; .pt-xxl-1 {

&#x20;   padding-top: 0.25rem !important;

&#x20; }

&#x20; .pt-xxl-2 {

&#x20;   padding-top: 0.5rem !important;

&#x20; }

&#x20; .pt-xxl-3 {

&#x20;   padding-top: 1rem !important;

&#x20; }

&#x20; .pt-xxl-4 {

&#x20;   padding-top: 1.5rem !important;

&#x20; }

&#x20; .pt-xxl-5 {

&#x20;   padding-top: 3rem !important;

&#x20; }

&#x20; .pe-xxl-0 {

&#x20;   padding-right: 0 !important;

&#x20; }

&#x20; .pe-xxl-1 {

&#x20;   padding-right: 0.25rem !important;

&#x20; }

&#x20; .pe-xxl-2 {

&#x20;   padding-right: 0.5rem !important;

&#x20; }

&#x20; .pe-xxl-3 {

&#x20;   padding-right: 1rem !important;

&#x20; }

&#x20; .pe-xxl-4 {

&#x20;   padding-right: 1.5rem !important;

&#x20; }

&#x20; .pe-xxl-5 {

&#x20;   padding-right: 3rem !important;

&#x20; }

&#x20; .pb-xxl-0 {

&#x20;   padding-bottom: 0 !important;

&#x20; }

&#x20; .pb-xxl-1 {

&#x20;   padding-bottom: 0.25rem !important;

&#x20; }

&#x20; .pb-xxl-2 {

&#x20;   padding-bottom: 0.5rem !important;

&#x20; }

&#x20; .pb-xxl-3 {

&#x20;   padding-bottom: 1rem !important;

&#x20; }

&#x20; .pb-xxl-4 {

&#x20;   padding-bottom: 1.5rem !important;

&#x20; }

&#x20; .pb-xxl-5 {

&#x20;   padding-bottom: 3rem !important;

&#x20; }

&#x20; .ps-xxl-0 {

&#x20;   preenchimento-esquerdo: 0 !importante;

&#x20; }

&#x20; .ps-xxl-1 {

&#x20;   padding-left: 0.25rem !important;

&#x20; }

&#x20; .ps-xxl-2 {

&#x20;   padding-left: 0.5rem !important;

&#x20; }

&#x20; .ps-xxl-3 {

&#x20;   padding-left: 1rem !important;

&#x20; }

&#x20; .ps-xxl-4 {

&#x20;   padding-left: 1.5rem !important;

&#x20; }

&#x20; .ps-xxl-5 {

&#x20;   padding-left: 3rem !important;

&#x20; }

&#x20; .gap-xxl-0 {

&#x20;   lacuna: 0 !importante;

&#x20; }

&#x20; .gap-xxl-1 {

&#x20;   espaço: 0,25rem !importante;

&#x20; }

&#x20; .gap-xxl-2 {

&#x20;   espaço: 0,5rem !importante;

&#x20; }

&#x20; .gap-xxl-3 {

&#x20;   espaço: 1rem !importante;

&#x20; }

&#x20; .gap-xxl-4 {

&#x20;   espaço: 1,5rem !importante;

&#x20; }

&#x20; .gap-xxl-5 {

&#x20;   espaço: 3rem !importante;

&#x20; }

&#x20; .row-gap-xxl-0 {

&#x20;   espaçamento entre linhas: 0 !importante;

&#x20; }

&#x20; .row-gap-xxl-1 {

&#x20;   espaçamento entre linhas: 0,25rem !importante;

&#x20; }

&#x20; .row-gap-xxl-2 {

&#x20;   espaçamento entre linhas: 0,5rem !importante;

&#x20; }

&#x20; .row-gap-xxl-3 {

&#x20;   espaçamento entre linhas: 1rem !importante;

&#x20; }

&#x20; .row-gap-xxl-4 {

&#x20;   espaçamento entre linhas: 1,5rem !importante;

&#x20; }

&#x20; .row-gap-xxl-5 {

&#x20;   espaçamento entre linhas: 3rem !importante;

&#x20; }

&#x20; .column-gap-xxl-0 {

&#x20;   -moz-column-gap: 0 !important;

&#x20;   espaçamento entre colunas: 0 !importante;

&#x20; }

&#x20; .column-gap-xxl-1 {

&#x20;   -moz-column-gap: 0.25rem !important;

&#x20;   espaçamento entre colunas: 0,25rem !importante;

&#x20; }

&#x20; .column-gap-xxl-2 {

&#x20;   -moz-column-gap: 0.5rem !important;

&#x20;   espaçamento entre colunas: 0,5rem !importante;

&#x20; }

&#x20; .column-gap-xxl-3 {

&#x20;   -moz-column-gap: 1rem !important;

&#x20;   column-gap: 1rem !important;

&#x20; }

&#x20; .column-gap-xxl-4 {

&#x20;   -moz-column-gap: 1.5rem !important;

&#x20;   espaçamento entre colunas: 1,5rem !importante;

&#x20; }

&#x20; .column-gap-xxl-5 {

&#x20;   -moz-column-gap: 3rem !important;

&#x20;   column-gap: 3rem !important;

&#x20; }

&#x20; .text-xxl-start {

&#x20;   alinhamento de texto: esquerda !importante;

&#x20; }

&#x20; .text-xxl-end {

&#x20;   alinhamento de texto: direita !importante;

&#x20; }

&#x20; .text-xxl-center {

&#x20;   alinhamento de texto: centralizado !importante;

&#x20; }

}

@media (min-width: 1200px) {

&#x20; .fs-1 {

&#x20;   tamanho da fonte: 2,5rem !importante;

&#x20; }

&#x20; .fs-2 {

&#x20;   tamanho da fonte: 2rem !importante;

&#x20; }

&#x20; .fs-3 {

&#x20;   tamanho da fonte: 1,75rem !importante;

&#x20; }

&#x20; .fs-4 {

&#x20;   tamanho da fonte: 1,5rem !importante;

&#x20; }

}

@media print {

&#x20; .d-print-inline {

&#x20;   exibir: embutido !importante;

&#x20; }

&#x20; .d-print-inline-block {

&#x20;   exibir: inline-block !important;

&#x20; }

&#x20; .d-print-block {

&#x20;   exibir: bloco !importante;

&#x20; }

&#x20; .d-print-grid {

&#x20;   exibir: grade !importante;

&#x20; }

&#x20; .d-print-inline-grid {

&#x20;   exibição: grade em linha !importante;

&#x20; }

&#x20; .d-print-table {

&#x20;   exibir: tabela !importante;

&#x20; }

&#x20; .d-print-table-row {

&#x20;   exibir: linha-da-tabela !importante;

&#x20; }

&#x20; .d-print-table-cell {

&#x20;   exibir: célula-da-tabela !importante;

&#x20; }

&#x20; .d-print-flex {

&#x20;   exibir: flex !importante;

&#x20; }

&#x20; .d-print-inline-flex {

&#x20;   exibir: inline-flex !important;

&#x20; }

&#x20; .d-print-none {

&#x20;   exibir: nenhum !importante;

&#x20; }

}



/\*# sourceMappingURL=bootstrap.css.map \*/

