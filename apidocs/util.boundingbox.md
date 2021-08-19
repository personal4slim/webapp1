<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@jsplumb/util](./util.md) &gt; [BoundingBox](./util.boundingbox.md)

## BoundingBox type

Defines the bounding box for some element - its x/y location, width and height, and optionally the computed center, but that can of course be calculated from the other values. Internally there are times when the code has this to hand so we include it here.

<b>Signature:</b>

```typescript
export declare type BoundingBox = {
    x: number;
    y: number;
    w: number;
    h: number;
    center?: PointXY;
};
```
<b>References:</b> [PointXY](./util.pointxy.md)
