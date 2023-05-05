# CSharpToJavaToTypeScript

#JavaScript
```javascript
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
```

#TypeScript
```TypeScript
class Dog {
    public Name: string;
    public Breed: string;
  
    constructor(name: string, breed: string) {
      this.Name = name;
      this.Breed = breed;
    }
  
    public Bark(): string {
      return "Woof!";
    }
  }
  
  const dogBreeds: string[] = ["Labrador", "Golden Retriever", "Bulldog"];
  
  class Random {
    public Next(maxValue: number): number {
      return Math.floor(Math.random() * maxValue);
    }
  }
  

  function GetRandomBreed(breeds: string[]): string {
    const random = new Random();
    const index = random.Next(breeds.length);
    return breeds[index];
  }
  
  
  // Testing the GetRandomBreed functions
  console.log(GetRandomBreed(dogBreeds));
  
```

