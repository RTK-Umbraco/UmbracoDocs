---
title: Amount
description: API reference for Amount in Umbraco Commerce
---
## Amount

An amount object

```csharp
public class Amount : ValueObjectBase, IAmount
```

**Inheritance**

* class [ValueObjectBase](../../umbraco-commerce-common/umbraco-commerce-common-models/valueobjectbase.md)
* interface [IAmount](iamount.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Constructors

#### Amount (1 of 2)

Instantiates a new [`Amount`](amount.md) instance

```csharp
public Amount(decimal value, Guid currencyId)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| value | The value of the amount |
| currencyId | The ID of the [`Currency`](currency.md) of the amount |

---

#### Amount (2 of 2)

Instantiates a new [`Amount`](amount.md) instance

```csharp
public Amount(decimal value, CurrencyReadOnly currency)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| value | The value of the amount |
| currency | The [`Currency`](currency.md) of the amount |


### Properties

#### CurrencyId

Gets the ID of the [`Currency`](currency.md) of the amount

```csharp
public Guid CurrencyId { get; }
```


---

#### Value

Gets the value of the amount

```csharp
public decimal Value { get; }
```


### Methods

#### OfSameCurrency

Create a new [`Amount`](amount.md) of the same [`Currency`](currency.md) as an existing amount

```csharp
public static Amount OfSameCurrency(Amount existingAmount, decimal value)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| existingAmount | The existing [`Amount`](amount.md) instance |
| value | The value of the new amount |

**Returns**

A new [`Amount`](amount.md) instance


---

#### ZeroValue

Instantiates a new [`Amount`](amount.md) instance with a zero value

```csharp
public static Amount ZeroValue(Guid currencyId)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| currencyId | The ID of the [`Currency`](currency.md) of the amount |

**Returns**

A zero value [`Amount`](amount.md) instance


---

#### DeepClone

```csharp
public override object DeepClone()
```


---

#### Rounded

Round the price to the given preceission

```csharp
public Amount Rounded(int decimalPlaces)
```

**Returns**

A rounded price value


### Operators

#### Amount Addition

```csharp
public static Amount operator +(Amount amount1, Amount amount2)
```


---

#### Amount Implicit

```csharp
public static implicit operator decimal(Amount amount)
```


---

#### Amount Subtraction

```csharp
public static Amount operator -(Amount amount1, Amount amount2)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
