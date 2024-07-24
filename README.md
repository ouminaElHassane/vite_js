# vite_js
apprendre vite


# javascript

## >principal langage de script coté navigateur
## >langage polyvalent : nodejs, bun, Deno en dehors de navigateur (pc,ordinateur, server, ecrire serveur, lire ecrire des fichiers,creer des outils pour l'embarque...)
## >Tres Ecosysteme +Community (librairie, reutilisation duc code , support)
## >Javascript n'est pas JAVA (marketing)
## >ECMASCRIPT : ECMAScript 6
## >ECMAScript 2015 was the second major revision to JavaScript.
## >ECMAScript 2015 is also known as ES6 and ECMAScript 6.
## >Javascript =Langage
## >ECMA =Organisme de standarisation
## >le standard ECMA-262 =ECMAScript <img src="https://github.com/user-attachments/assets/6bbb67f9-e8da-487e-8396-748f29fc6fdc" alt="Description of Image" height="16"> Language specification
## >ECMASCRIPT 2015 (ECMAScript 6), ECMAScript2022, ES2022 ( je fais Javascript aux standards de ECMAASCRIPT [ANNEE]), se situé dans le fonctionnement de langage

# Prerequis :

## Algorithmie
## Visual studio
## HTML/CSS (coté navigateur)
## Http (coté serveur)

# Déroulé de la formation :
### Apprendre les bases du language
### javascript dans le navigateur
### javascript coté serveur

### <script> </script>
### mdn
### variable const


<script> 
const a = 3 ;
  let b=3 ;
  b=4 ;
  var (ancien)
  const c = 2
  const une_variable_plus_longue = "Ma super chaîne"
let a = 2
a = "Je suis une chaîne maintenant !"
  backtick alt GR + 7  =`     `
</script>
function example() {
    console.log(x); // undefined
    // console.log(y); // ReferenceError: Cannot access 'y' before initialization
    // console.log(z); // ReferenceError: Cannot access 'z' before initialization

    var x = 1;
    let y = 2;
    const z = 3;

    console.log(x); // 1
    console.log(y); // 2
    console.log(z); // 3

    // Re-declaration examples:
    var x = 10; // Allowed with var
    // let y = 20; // SyntaxError: Identifier 'y' has already been declared
    // const z = 30; // SyntaxError: Identifier 'z' has already been declared

    // Assignment examples:
    x = 100; // Allowed
    y = 200; // Allowed
    // z = 300; // TypeError: Assignment to constant variable.
}
example();

 function mapFonction() {
            console.log(this)
        }

        mapFonction.call(3)
        --------------

          const a = {

            firstname: 'John',
            lastname: 'Doe',
            fullname: function () {// method de l'objet a
                console.log(`${this.firstname} ${this.lastname}`) 
            }

        }


       a.fullname()


       ---------------function en parametre de function :callback ------

       const isPair =function (a, fn){
        
        if(a%2===0){
           fn()
         }
       }

       isPair(4, function(){
        console.log('Mon Nombre est pair')
       }
       )

       -----------------

        const isPair =function (a, cb){
        
        if(a%2===0){
           cb(a)
         }
       }

       isPair(4, function(n){
        console.log('Mon Nombre est pair ' + n)
       }
       )

       -----------------

       function isPremier(n){
        if(n < 2){
            return false
        }
        for (let i=n-1; i>1 ; i--){

            if(n% i===0){
                return false;
            }
        
        }
        return true
      }
      console.log('0', isPremier(0))
      console.log('1', isPremier(1))
      console.log('2', isPremier(2))
      console.log('3', isPremier(3))
      console.log('4', isPremier(4))
      console.log('5', isPremier(5))
      console.log('6', isPremier(6))
      console.log('7', isPremier(7))
      console.log('8', isPremier(8))
      console.log('9', isPremier(9))
      console.log('10', isPremier(10))
      console.log('11', isPremier(11))
      console.log('12', isPremier(12))

