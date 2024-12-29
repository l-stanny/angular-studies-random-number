# Angular Studies

These self-directed study projects were generated in an [Nx](https://nx.dev) monorepo and are in this repository *in part*.

<p style="text-align: center;"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="450"></p>

🔎 **Powerful, Extensible Dev Tools**

[Nx Documentation](https://nx.dev/angular)

## Random Numbers Study
Demonstrates Javascript, Typescript, Angular interpolation - one-way data binding -, and the Angular ngModel directive's two-way data binding technique which is used to autofill the editable form fields. When the form fields are filled out by the user and the "Generate" button is clicked, the username and a random integer between 1 and 9 are rendered in the DOM.

https://github.com/user-attachments/assets/35c96b62-1d58-436f-89a3-79b672ab6844


## Reddit-like Study
Allows the user to post an article (with a title and a URL) and vote on the posts. Voting uses increment and decrement to dynamically sort articles by number of votes.

It has 2 components:

1 to hold the form that submits an article. It binds the submit value in the view to entered text in the inputs using the hash, resolve, syntax then gets the data into the component as objects of the type HTMLInputElement.

1 to hold the default and newly submitted articles using @Hostbinding to bind a class to the host app. It uses a model to isolate the data structures.
