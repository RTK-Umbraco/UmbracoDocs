---
title: OrderedComposedCollectionBuilderBase<TBuilder,TCollection,TItem>
description: API reference for OrderedComposedCollectionBuilderBase<TBuilder,TCollection,TItem> in Umbraco Commerce
---
## OrderedComposedCollectionBuilderBase&lt;TBuilder,TCollection,TItem&gt;

```csharp
public abstract class OrderedComposedCollectionBuilderBase<TBuilder, TCollection, TItem> : 
    ComposedCollectionBuilderBase<TBuilder, TCollection, TItem>, 
    IOrderedComposedCollectionBuilder<TBuilder, TCollection, TItem>
    where TBuilder : OrderedComposedCollectionBuilderBase<TBuilder, TCollection, TItem>
    where TCollection : class, IComposedCollection<TItem>
```

**Inheritance**

* class [ComposedCollectionBuilderBase&lt;TBuilder,TCollection,TItem&gt;](composedcollectionbuilderbase-3.md)
* interface [IOrderedComposedCollectionBuilder&lt;TBuilder,TCollection,TItem&gt;](iorderedcomposedcollectionbuilder-3.md)

**Namespace**
* [Umbraco.Commerce.Common.Composing](README.md)

### Methods

#### Insert (1 of 2)

```csharp
public TBuilder Insert(Type type)
```

---

#### Insert (2 of 2)

```csharp
public TBuilder Insert(int index, Type type)
```


---

#### Insert&lt;T&gt;

```csharp
public TBuilder Insert<T>(int index = 0)
    where T : TItem
```


---

#### InsertAfter

```csharp
public TBuilder InsertAfter(Type typeAfter, Type type)
```


---

#### InsertAfter&lt;TAfter,T&gt;

```csharp
public TBuilder InsertAfter<TAfter, T>()
    where TAfter : TItem
    where T : TItem
```


---

#### InsertBefore

```csharp
public TBuilder InsertBefore(Type typeBefore, Type type)
```


---

#### InsertBefore&lt;TBefore,T&gt;

```csharp
public TBuilder InsertBefore<TBefore, T>()
    where TBefore : TItem
    where T : TItem
```


---

#### Replace

```csharp
public TBuilder Replace(Type typeReplaced, Type type)
```


---

#### Replace&lt;TReplaced,T&gt;

```csharp
public TBuilder Replace<TReplaced, T>()
    where TReplaced : TItem
    where T : TItem
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Common.dll -->
