<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@jsplumb/core](./core.md) &gt; [EndpointFactory](./core.endpointfactory.md)

## EndpointFactory variable

<b>Signature:</b>

```typescript
EndpointFactory: {
    get: (ep: Endpoint<any>, name: string, params: any) => EndpointRepresentation<any>;
    clone: <C>(epr: EndpointRepresentation<C>) => EndpointRepresentation<C>;
    compute: <T>(endpoint: EndpointRepresentation<T>, anchorPoint: AnchorPlacement, orientation: [number, number], endpointStyle: any) => T;
    registerHandler: <E, T>(eph: EndpointHandler<E, T>) => void;
}
```