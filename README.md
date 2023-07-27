# UICollectionViewSupplementaryRegistration
Let's improve the inconvenience of UICollectionViewSupplementary.Registration

I was very strange using UICollectionView 's Registration .

CellRegistration can receive and use two Generic Types,
Why can SupplementaryRegistration only use one Generic Type?

So when we use SupplemenrayRegistration, we can't pure it and we have to refer to the value from the outside and use it.

That's why I made an extension.

Now we don't have to reference the value outside of SupplementaryRegistration.
