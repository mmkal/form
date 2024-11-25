---
id: DerivedFormState
title: DerivedFormState
---

# Type Alias: DerivedFormState

```ts
type DerivedFormState: object;
```

## Type declaration

### canSubmit

```ts
canSubmit: boolean;
```

A boolean indicating if the form can be submitted based on its current state.

### errors

```ts
errors: ValidationError[];
```

The error array for the form itself.

### isBlurred

```ts
isBlurred: boolean;
```

A boolean indicating if any of the form fields have been blurred.

### isDirty

```ts
isDirty: boolean;
```

A boolean indicating if any of the form's fields' values have been modified by the user. `True` if the user have modified at least one of the fields. Opposite of `isPristine`.

### isFieldsValid

```ts
isFieldsValid: boolean;
```

A boolean indicating if all the form fields are valid.

### isFieldsValidating

```ts
isFieldsValidating: boolean;
```

A boolean indicating if any of the form fields are currently validating.

### isFormValid

```ts
isFormValid: boolean;
```

A boolean indicating if the form is valid.

### isFormValidating

```ts
isFormValidating: boolean;
```

A boolean indicating if the form is currently validating.

### isPristine

```ts
isPristine: boolean;
```

A boolean indicating if none of the form's fields' values have been modified by the user. `True` if the user have not modified any of the fields. Opposite of `isDirty`.

### isTouched

```ts
isTouched: boolean;
```

A boolean indicating if any of the form fields have been touched.

### isValid

```ts
isValid: boolean;
```

A boolean indicating if the form and all its fields are valid.

## Defined in

[packages/form-core/src/FormApi.ts:263](https://github.com/TanStack/form/blob/main/packages/form-core/src/FormApi.ts#L263)