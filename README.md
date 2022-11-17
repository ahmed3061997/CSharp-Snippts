# C# Code Snippets for Visual Studio

- automap
> Create a mapping between two types ( [AutoMapper](https://automapper.org/) )
```
CreateMap<SourceType, TargetType>();
```

- validator
> Create a template validator class ( [FluentValidation](https://fluentvalidation.net/) )
```
public class Validator : AbstractValidator<T>
{
    public Validator()
    {
        RuleFor(x => x.Prop).NotEmpty();
    }
}
```
