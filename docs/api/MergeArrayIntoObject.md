# MergeArrayIntoObject

## Namespace

```php
use ISQ\MAIO\MergeArrayIntoObject;
```

## Setting

---

> ### CheckSnakeCase
>
> Define to check snake case on merge property
>
> ```php
> MergeArrayIntoObject::checkSnakeCase = true;
> ```

---

---

> ### CheckCamelCase
>
> Define to check camel case on merge property
>
> ```php
> MergeArrayIntoObject::checkCamelCase = true;
> ```

---

## Methods

---

> ### getInstance()
>
> Returns a class already instantiated.
>
> > **Return:** `MergeArrayIntoObject`
>
> ```php
> MergeArrayIntoObject::getInstance();
> ```

---

---

> ### merge()
>
> Merge `data` in `target` class
>
> > **arg0(target):** `T`
> >
> > **arg1(data):** `array|null`
> >
> > **Return:** `T`
>
> ```php
> $maio = new MergeArrayIntoObject();
> $maio->merge($targe, $data);
> ```

---
