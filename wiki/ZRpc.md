C:\Users\marve\source\repos\Valheim-Networking-Wiki\Valheim-Networking-Wiki.wiki\ZRpc.md

## Void Dispose()

## ISocket GetSocket()

## ErrorCode Update(Single)

## Void UpdatePing(Single)

## Void ReceivePing(ZPackage)

## Single GetTimeSinceLastPing()

## Boolean IsConnected()

## Void HandlePackage(ZPackage)

## Void Register(System.String, Method)

## Void Register[T](System.String, System.Action`2[ZRpc,T])

## Void Register[T,U](System.String, System.Action`3[ZRpc,T,U])

## Void Register[T,U,V](System.String, System.Action`4[ZRpc,T,U,V])

## Void Register[T,U,V,W](System.String, Method)

## Void Unregister(System.String)

## Void Invoke(System.String, System.Object[])

## Void SendPackage(ZPackage)

## Void Serialize(System.Object[], ZPackage ByRef)

## System.Object[] Deserialize(ZRpc, System.Reflection.ParameterInfo[], ZPackage)

## Void Deserialize(System.Reflection.ParameterInfo[], ZPackage, System.Collections.Generic.List`1[System.Object] ByRef)

## Void SetLongTimeout(Boolean)