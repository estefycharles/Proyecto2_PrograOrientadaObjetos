# Proyecto2_PrograOrientadaObjetos

class Pelicula
{
private:
    int numPeli;
    string titulo;
    int anio;
    int duracion;
    string genero;
    int cantActores;
    //falta declarar el arreglo listaActores
    
public:
    Pelicula(); //constructor default
    //metodos de modificacion
    void setNumPeli(int nP){
        numPeli = nP;
    }; 
    void setTitulo(string tit){
        titulo = tit;
    };
    void setAnio(int a){
        anio = a;
    };
    void setDuracion(int dur){
        duracion = dur;
    };
    void setGenero(string gen){
        genero = gen;
    };
    //metodos de acceso
    int getNumpeli(){
        return numPeli;
    }; 
    string getTitulo(){
        return titulo;
    };
    int getAnio(){
        return anio;
    };
    int getDuracion(){
        return duracion;
    };
    string getGenero(){
        return genero;
    };
    int getCantActores(){
        return cantActores;
    };
    
};
//Definicion de funciones

Pelicula::Pelicula(){ //constructor default
    numPeli = 0;
    titulo = "N/A";
    anio = 0;
    duracion = 0;
    genero = "N/A";
}

