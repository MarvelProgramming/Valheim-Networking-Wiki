C:\Users\marve\source\repos\Valheim-Networking-Wiki\Valheim-Networking-Wiki.wiki\ZDOMan.md

## Void ResetSectorArray()

## Void ShutDown()

## Void PrepareSave()

## Void SaveAsync(System.IO.BinaryWriter)

## Void Load(System.IO.BinaryReader, Int32)

## Void RemoveOldGeneratedZDOS()

## Void CapDeadZDOList()

## ZDO CreateNewZDO(UnityEngine.Vector3)

## ZDO CreateNewZDO(ZDOID, UnityEngine.Vector3)

## Void AddToSector(ZDO, Vector2i)

## Void ZDOSectorInvalidated(ZDO)

## Void RemoveFromSector(ZDO, Vector2i)

## ZDO GetZDO(ZDOID)

## Void AddPeer(ZNetPeer)

## Void RemovePeer(ZNetPeer)

## ZDOPeer FindPeer(ZNetPeer)

## ZDOPeer FindPeer(ZRpc)

## Void Update(Single)

## Void UpdateStats(Single)

## Void SendZDOToPeers(Single)

## Void SendZDOToPeers2(Single)

## Void FlushClientObjects()

## Void ReleaseZDOS(Single)

## Boolean IsInPeerActiveArea(Vector2i, Int64)

## Void ReleaseNearbyZDOS(UnityEngine.Vector3, Int64)

## Void DestroyZDO(ZDO)

## Void SendDestroyed()

## Void RPC_DestroyZDO(Int64, ZPackage)

## Void HandleDestroyedZDO(ZDOID)

## Void SendAllZDOs(ZDOPeer)

## Boolean SendZDOs(ZDOPeer, Boolean)

## Void RPC_ZDOData(ZRpc, ZPackage)

## Void FindSectorObjects(Vector2i, Int32, Int32, System.Collections.Generic.List`1[ZDO], System.Collections.Generic.List`1[ZDO])

## Void FindSectorObjects(Vector2i, Int32, System.Collections.Generic.List`1[ZDO])

## Void CreateSyncList(ZDOPeer, System.Collections.Generic.List`1[ZDO])

## Void AddForceSendZdos(ZDOPeer, System.Collections.Generic.List`1[ZDO])

## Int32 ServerSendCompare(ZDO, ZDO)

## Void ServerSortSendZDOS(System.Collections.Generic.List`1[ZDO], UnityEngine.Vector3, ZDOPeer)

## Int32 ClientSendCompare(ZDO, ZDO)

## Void ClientSortSendZDOS(System.Collections.Generic.List`1[ZDO], ZDOPeer)

## Void PrintZdoList(System.Collections.Generic.List`1[ZDO])

## Void AddDistantObjects(ZDOPeer, Int32, System.Collections.Generic.List`1[ZDO])

## Int64 GetMyID()

## Int32 SectorToIndex(Vector2i)

## Void FindObjects(Vector2i, System.Collections.Generic.List`1[ZDO])

## Void FindDistantObjects(Vector2i, System.Collections.Generic.List`1[ZDO])

## Void RemoveOrphanNonPersistentZDOS()

## Boolean IsPeerConnected(Int64)

## Void GetAllZDOsWithPrefab(System.String, System.Collections.Generic.List`1[ZDO])

## Boolean InvalidZDO(ZDO)

## Boolean GetAllZDOsWithPrefabIterative(System.String, System.Collections.Generic.List`1[ZDO], Int32 ByRef)

## System.Collections.Generic.List`1[ZDO] GetSaveClone()

## Int32 NrOfObjects()

## Int32 GetSentZDOs()

## Int32 GetRecvZDOs()

## Void GetAverageStats(Single ByRef, Single ByRef)

## Int32 GetClientChangeQueue()

## Void RequestZDO(ZDOID)

## Void RPC_RequestZDO(Int64, ZDOID)

## ZDOPeer GetPeer(Int64)

## Void ForceSendZDO(ZDOID)

## Void ForceSendZDO(Int64, ZDOID)

## Void ClientChanged(ZDOID)

## System.Collections.Generic.List`1[ZDO] GetSaveClone()

## System.Collections.Generic.List`1[ZDO] GetSaveClone()