const nombres = ['Hugo', 'Paco', 'Luis', 'Pedro', 'Hector'];
const edades = [35, 50, 40, 18, 30];

const obtenerIndiceEdadMenor = () => {
    let menor = edades[0];
    let indiceMenor = 0;
    for (let i = 1; i < edades.length; i++) {
        if (edades[i] < menor) {
            menor = edades[i];
            indiceMenor = i;
        }
    }
    return indiceMenor;
};

const obtenerIndiceEdadMayor = () => {
    let mayor = edades[0];
    let indiceMayor = 0;
    for (let i = 1; i < edades.length; i++) {
        if (edades[i] > mayor) {
            mayor = edades[i];
            indiceMayor = i;
        }
    }
    return indiceMayor;
};

const mensajeEdadMenor = () => {
    const i = obtenerIndiceEdadMenor();
    return `${nombres[i]} es el menor con ${edades[i]} años.`;
};

const mensajeEdadMayor = () => {
    const i = obtenerIndiceEdadMayor();
    return `${nombres[i]} es el mayor con ${edades[i]} años.`;
};

console.log(mensajeEdadMenor());
console.log(mensajeEdadMayor());
