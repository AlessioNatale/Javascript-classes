# Classes

Create a class called Developer. The Developer class has to inherit the Person class created in the previous exercise. The Developer class takes in another argument in the constructor method (role).

class Person {
constructor(firstName, lastName) {
this.firstName = firstName;
this.lastName = lastName;
}
}

const developer = new Developer("Mario", "Rossi", "Front-end");
console.log(developer.firstName + " " + developer.lastName + " " + developer.role);


Crea una classe chiamata Sviluppatore. La classe Developer deve ereditare la classe Person creata nell'esercizio precedente. La classe Developer accetta un altro argomento nel metodo del costruttore (ruolo).

persona di classe {
costruttore(nome, cognome) {
this.firstName = primoNome;
this.cognome = cognome;
}
}

const sviluppatore = nuovo Sviluppatore("Mario", "Rossi", "Front-end");
console.log(sviluppatore.primoNome + " " + sviluppatore.cognome + " " + sviluppatore.ruolo);