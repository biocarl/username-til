# username-til

This is my personal readme file.
The part before the divder won't be shown!!

---


# 📅 09.03.2023 git: How to undo the last commit but keep the changes in working directory?
- Either soft-reset via cli: `git reset HEAD~1 --soft`
- Some more bullet points

# 📅 01.03.2023 angular: How to inject something into a component?
- Just provide it **with an access modifier** to the constructor of your component
```javascript
export class SomeService {
  constructor(
    private http: HttpClient
  ) {}
}
```
- Different access modifiers have different effects
- `private`  only works inside component
- `protected` can also be accessed from template
- `public` also works
- If you omit the modifier it is not a class variable but merely a method parameter, or put the other way round: If you provide an access modifier the field automatically gets promoted to a class variable.
