# Product Card
This is a package for testing deployments on NPM

### Jair Jimenez

## Example
```
import { 
  ProductButtons, 
  ProductCard, 
  ProductImage, 
  ProductTitle 
} from 'jj-product-card'
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 4,
        maxCount: 10
    }}>
    {({ count, isMaxCountReached, reset, increaseBy }) => (
        <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
        </>
    )}
</ProductCard>
```