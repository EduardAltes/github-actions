# Laravel Test - Integració de GitHub Actions

[![LaravelTest](https://github.com/EduardAltes/github-actions/actions/workflows/laravel.yml/badge.svg)](https://github.com/EduardAltes/github-actions/actions/workflows/laravel.yml)

## Descripció

Aquest repositori té com a objectiu automatitzar l'execució de proves unitàries utilitzant GitHub Actions per al projecte de TDD "Cuenta" desenvolupat prèviament. El procés inclou la configuració d'un entorn de treball adequat i l'execució de les proves per garantir que el codi funciona correctament en tot moment.

## Passos per a la configuració

1. **Crea un Repositori a GitHub**  
   Inicialitza un nou repositori a GitHub per al projecte.

2. **Puja el Projecte a GitHub**  
   Un cop creat el repositori, puja tot el codi font del projecte, incloent-hi els fitxers necessaris per a l'execució i les proves unitàries escrites seguint la metodologia TDD.

3. **Configura GitHub Actions**  
   Configura un *GitHub Action* per automatitzar l'execució de les proves unitàries amb cada *push* que facis al repositori. Utilitza les plantilles de GitHub per configurar l'acció per a Laravel.

4. **Executa el Workflow**  
   Un cop configurat, fes un *push* al repositori per activar l'execució del workflow. Això farà que es duguin a terme les proves automàticament, validant la funcionalitat del teu codi.

5. **Modifica el Workflow per Laravel**  
   Actualitza el workflow per complir els requisits actuals de Laravel. Això pot incloure la versió de PHP o qualsevol altra dependència necessària per al correcte funcionament de Laravel.

## Instruccions Addicionals

- **Actualització de dependències**: Assegura't que les dependències, com la versió de PHP i altres biblioteques necessàries, estiguin actualitzades i configurades correctament dins del workflow de GitHub Actions.
  
## License

El framework Laravel és un programari de codi obert llicenciat sota la [llicència MIT](https://opensource.org/licenses/MIT).

