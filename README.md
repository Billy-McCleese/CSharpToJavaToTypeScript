# CSharpToJavaToTypeScript

#Java

class Dog 
{
    constructor(name, breed)
    {
        this.Name = name
        this.Breed = breed
    }

    Bark() 
    {
        return "Woof!"
    }
}

const DogBreeds = ["Labrador", "Golden Retriever", "Bulldog"];

function GetRandomBreed(breeds)
{
    const random = new Random();
    const index = random.Next(breeds.length);
    return breeds[index];
}

