C:\Users\marve\source\repos\Valheim-Networking-Wiki\Valheim-Networking-Wiki.wiki\ZNet.md

## Void UpdatePlayerList()

## Void SendPlayerList()

## Void RPC_PlayerList(ZRpc, ZPackage)

## System.Collections.Generic.List`1[ZNet+PlayerInfo] GetPlayerList()

## Void GetOtherPublicPlayers(System.Collections.Generic.List`1[ZNet+PlayerInfo])

## Int32 GetNrOfPlayers()

## Void GetNetStats(Single ByRef, Single ByRef, Int32 ByRef, Single ByRef, Single ByRef)

## Void SetNetTime(Double)

## System.DateTime GetTime()

## Single GetWrappedDayTimeSeconds()

## Double GetTimeSeconds()

## ConnectionStatus GetConnectionStatus()

## Boolean HasBadConnection()

## Single GetServerPing()

## ZNetPeer GetServerPeer()

## ZRpc GetServerRPC()

## System.Collections.Generic.List`1[ZNetPeer] GetPeers()

## Void RemotePrint(ZRpc, System.String)

## Void RPC_RemotePrint(ZRpc, System.String)

## Void Kick(System.String)

## Void RPC_Kick(ZRpc, System.String)

## Void RPC_Kicked(ZRpc)

## Void InternalKick(System.String)

## Void InternalKick(ZNetPeer)

## Boolean IsAllowed(System.String, System.String)

## Void Ban(System.String)

## Void RPC_Ban(ZRpc, System.String)

## Void InternalBan(ZRpc, System.String)

## Void Unban(System.String)

## Void RPC_Unban(ZRpc, System.String)

## Void InternalUnban(ZRpc, System.String)

## Void PrintBanned()

## Void RPC_PrintBanned(ZRpc)

## Void InternalPrintBanned(ZRpc)

## System.String ServerPasswordSalt()

## Void SetExternalError(ConnectionStatus)

## Void <OnSteamServerRegistered>g__RetryRegisterAfterDelay|7_0(Single)

## System.Collections.IEnumerator <OnSteamServerRegistered>g__DelayThenRegisterCoroutine|7_1(Single)

## System.String <SaveWorldThread>g__GetBackupPath|59_0(System.String, System.DateTime)

## Void Awake()

## Void Start()

## System.String GetServerIP()

## System.String LocalIPAddress()

## System.String GetPublicIP()

## Void OnSteamServerRegistered(Boolean)

## Void Shutdown()

## Void StopAll()

## Void OnDestroy()

## ZNetPeer Connect(ISocket)

## Void Connect(System.String)

## Void Connect(Steamworks.CSteamID)

## Void Connect(Steamworks.SteamNetworkingIPAddr)

## Void Connect(System.String, Int32)

## Void UpdateClientConnector(Single)

## Void OnNewConnection(ZNetPeer)

## Void RPC_ServerHandshake(ZRpc)

## Void UpdatePassword()

## Boolean InPasswordDialog()

## Void RPC_ClientHandshake(ZRpc, Boolean, System.String)

## Void OnPasswordEnter(System.String)

## Void OnPasswordOk()

## Void SendPeerInfo(ZRpc, System.String)

## Void RPC_PeerInfo(ZRpc, ZPackage)

## Void SendDisconnect()

## Void SendDisconnect(ZNetPeer)

## Void RPC_Disconnect(ZRpc)

## Void RPC_Error(ZRpc, Int32)

## Boolean IsConnected(Int64)

## Void ClearPlayerData(ZNetPeer)

## Void Disconnect(ZNetPeer)

## Void FixedUpdate()

## Void Update()

## Void LateUpdate()

## Void UpdateNetTime(Single)

## Void UpdateBanList(Single)

## Void CheckWhiteList()

## Boolean IsSaving()

## Void ConsoleSave()

## Void RPC_Save(ZRpc)

## Boolean ListContainsId(SyncedList, System.String)

## Void Save(Boolean)

## World GetWorldIfIsHost()

## Void SendPeriodicData(Single)

## Void SendNetTime()

## Void RPC_NetTime(ZRpc, Double)

## Void RPC_RefPos(ZRpc, UnityEngine.Vector3, Boolean)

## Void UpdatePeers(Single)

## Void CheckForIncommingServerConnections()

## ZNetPeer GetPeerByPlayerName(System.String)

## ZNetPeer GetPeerByHostName(System.String)

## ZNetPeer GetPeer(Int64)

## ZNetPeer GetPeer(ZRpc)

## System.Collections.Generic.List`1[ZNetPeer] GetConnectedPeers()

## Void SaveWorld(Boolean)

## Void UpdateSave()

## Void SaveWorldThread()

## Boolean ConsiderAutoBackup(System.String, FileSource, System.DateTime)

## Void LoadWorld()

## Boolean CheckDataVersion(System.IO.BinaryReader, Int32 ByRef)

## Int32 GetHostPort()

## Int64 GetUID()

## Int64 GetWorldUID()

## System.String GetWorldName()

## Void SetCharacterID(ZDOID)

## Void RPC_CharacterID(ZRpc, ZDOID)

## Void SetPublicReferencePosition(Boolean)

## Boolean IsReferencePositionPublic()

## Void SetReferencePosition(UnityEngine.Vector3)

## UnityEngine.Vector3 GetReferencePosition()

## System.Collections.Generic.List`1[ZDO] GetAllCharacterZDOS()

## Int32 GetPeerConnections()

## ZNat GetZNat()

## Void SetServer(Boolean, Boolean, Boolean, System.String, System.String, World)

## System.String HashPassword(System.String, System.String)

## Void ResetServerHost()

## Boolean HasServerHost()

## Void SetServerHost(System.String)

## Void SetServerHost(UInt64)

## Void SetServerHost(System.String, Int32, OnlineBackendType)

## System.String GetServerString(Boolean)

## Boolean IsServer()

## Boolean IsDedicated()

## System.Collections.Generic.List`1[ZNet+PlayerInfo] GetPlayerList()

## System.Collections.Generic.List`1[ZNetPeer] GetPeers()

## Void <OnSteamServerRegistered>g__RetryRegisterAfterDelay|7_0(Single)

## System.Collections.IEnumerator <OnSteamServerRegistered>g__DelayThenRegisterCoroutine|7_1(Single)

## System.String <SaveWorldThread>g__GetBackupPath|59_0(System.String, System.DateTime)

## System.Collections.Generic.List`1[ZNetPeer] GetConnectedPeers()

## System.Collections.Generic.List`1[ZDO] GetAllCharacterZDOS()

## System.Collections.Generic.List`1[ZNet+PlayerInfo] GetPlayerList()

## System.Collections.Generic.List`1[ZNetPeer] GetPeers()

## Void <OnSteamServerRegistered>g__RetryRegisterAfterDelay|7_0(Single)

## System.Collections.IEnumerator <OnSteamServerRegistered>g__DelayThenRegisterCoroutine|7_1(Single)

## System.String <SaveWorldThread>g__GetBackupPath|59_0(System.String, System.DateTime)

## System.Collections.Generic.List`1[ZNetPeer] GetConnectedPeers()

## System.Collections.Generic.List`1[ZDO] GetAllCharacterZDOS()