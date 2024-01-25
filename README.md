# timestamppb

This go module provides a `Timestamp` type that is compatible with the `database/sql` package within the go standard library. This makes it compatible with ORMs such as Bun out of the box. This is done by implementing the `Scan()` and `Value()` methods on the `Timestamp` type. Other than those added messages this type is no different than the `timestamppb.Timestamp` type provided by the `google.golang.org/protobuf/types/known/timestamppb` package.
