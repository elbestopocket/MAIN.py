# MAIN.py
Archivo main donde se ejecuta el código de "Pelicula"
    
    from pelicula import Película  

    def main():
  
    peli1 = Película(1313, "Destino final: lazos de sangre", 109, "Zach Lipovsky & Adam Stein")
    peli2 = Película(6969, "Karate Kid: Leyendas", 94, "Jonathan Entwistle")
    peli3 = Película(1313, "Thunderbolts*", 126, "Jake Schreier")
  
    print("Información de las películas:")
    print(peli1)
    print(peli2)
    print(peli3)
    
    print("Prestando y devolviendo películas:")
    print(peli1.prestar())
    print(peli2.prestar())
    print(peli3.devolver())
  
    print("Costo de reproducción:")
    print(peli2.costo_reproducción(85))

    print("Comparando películas:")
    print("¿La película #1 y la película #2 tienen el mismo código?", peli1 == peli2)
    print("¿La película #2 y la película #3 tienen el mismo código?", peli2 == peli3)
  


    if __name__ == "__main__":
    main()

