---
title: DynamicEvent
---

## Summary

### Constructors

|  |
| --- |
| **[DynamicEvent](#constructor-0)**() |
| **[DynamicEvent](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "id" >}} | int |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [DynamicEvent](/vext/ref/fb/dynamicevent) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "DynamicEvent" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### DynamicEvent {#constructor-0}

> **DynamicEvent**()

Creates a new [DynamicEvent](/vext/ref/fb/dynamicevent) frostbite instance.

### DynamicEvent {#constructor-1}

> **DynamicEvent**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [DynamicEvent](/vext/ref/fb/dynamicevent) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "id" %}}

> **int**

## Methods

### Clone {#clone}

> **Clone**(): [DynamicEvent](/vext/ref/fb/dynamicevent)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[DynamicEvent](/vext/ref/fb/dynamicevent)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [DynamicEvent](/vext/ref/fb/dynamicevent) type.

