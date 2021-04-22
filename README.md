# Hey there, I'm Eliaser Concha

```Java

class Biography {
    private String name;
    private String lastName;
    private int age;
    private String country;
    private Hobbies hobbies;

    public Biography(){
        this.name = "Eliaser Alejandro";
        this.lastName = "Concha Sepúlveda";
        this.age = 21;
        this.country = "Chile";
        this.hobbies = new Hobbies();
        this.hobbies.add("Listen music");
        this.hobbies.add("Watch movies");
    }
}

class Student extends Biography {
    private String career;
    private String university;

    public Student(){
        super();
        this.career = "Ingeniería Civil en Informática";
        this.university = "Universidad Católica de Temuco";
    }
}

class Hobbies {
    private ArrayList<String> hobbies;

    public Hobbies() {
        this.hobbies = new ArrayList<>();
    }

    public void add(String action){
        if (!this.hobbies.contains(action)) {
            this.hobbies.add(action);
        }
    }
}

```

⭐️ From [eliasercs](https://github.com/eliasercs)