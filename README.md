# ds_lab9

{
	"set" : "rs0",
	"date" : ISODate("2019-11-01T19:02:21.422Z"),
	"myState" : 1,
	"term" : NumberLong(1),
	"syncingTo" : "",
	"syncSourceHost" : "",
	"syncSourceId" : -1,
	"heartbeatIntervalMillis" : NumberLong(2000),
	"majorityVoteCount" : 2,
	"writeMajorityCount" : 2,
	"optimes" : {
		"lastCommittedOpTime" : {
			"ts" : Timestamp(1572634941, 1),
			"t" : NumberLong(1)
		},
		"lastCommittedWallTime" : ISODate("2019-11-01T19:02:21.422Z"),
		"readConcernMajorityOpTime" : {
			"ts" : Timestamp(1572634941, 1),
			"t" : NumberLong(1)
		},
		"readConcernMajorityWallTime" : ISODate("2019-11-01T19:02:21.422Z"),
		"appliedOpTime" : {
			"ts" : Timestamp(1572634941, 1),
			"t" : NumberLong(1)
		},
		"durableOpTime" : {
			"ts" : Timestamp(1572634941, 1),
			"t" : NumberLong(1)
		},
		"lastAppliedWallTime" : ISODate("2019-11-01T19:02:21.422Z"),
		"lastDurableWallTime" : ISODate("2019-11-01T19:02:21.422Z")
	},
	"lastStableRecoveryTimestamp" : Timestamp(1572634941, 1),
	"lastStableCheckpointTimestamp" : Timestamp(1572634941, 1),
	"electionCandidateMetrics" : {
		"lastElectionReason" : "electionTimeout",
		"lastElectionDate" : ISODate("2019-11-01T19:02:21.422Z"),
		"termAtElection" : NumberLong(1),
		"lastCommittedOpTimeAtElection" : {
			"ts" : Timestamp(0, 0),
			"t" : NumberLong(-1)
		},
		"lastSeenOpTimeAtElection" : {
			"ts" : Timestamp(1572634941, 1),
			"t" : NumberLong(-1)
		},
		"numVotesNeeded" : 2,
		"priorityAtElection" : 1,
		"electionTimeoutMillis" : NumberLong(10000),
		"numCatchUpOps" : NumberLong(27017),
		"newTermStartDate" : ISODate("2019-11-01T19:02:21.422Z"),
		"wMajorityWriteAvailabilityDate" : ISODate("2019-11-01T19:02:21.420Z")
	},
	"members" : [
		{
			"_id" : 0,
			"name" : "m1:27017",
			"ip" : "172.36.36.105",
			"health" : 1,
			"state" : 1,
			"stateStr" : "PRIMARY",
			"uptime" : 102551,
			"optime" : {
				"ts" : Timestamp(1572634941, 1),
				"t" : NumberLong(1)
			},
			"optimeDate" : ISODate("2019-11-01T19:02:15.422Z"),
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"electionTime" : Timestamp(1572634941, 1),
			"electionDate" : ISODate("2019-11-01T19:02:21.422Z"),
			"configVersion" : 1,
			"self" : true,
			"lastHeartbeatMessage" : ""
		},
		{
			"_id" : 1,
			"name" : "m2:27017",
			"ip" : "172.31.30.157",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 101903,
			"optime" : {
				"ts" : Timestamp(1572634941, 1),
				"t" : NumberLong(1)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572634941, 1),
				"t" : NumberLong(1)
			},
			"optimeDate" : ISODate("2019-11-01T19:02:19.352Z"),
			"optimeDurableDate" : ISODate("2019-11-01T19:02:19.352Z"),
			"lastHeartbeat" : ISODate("2019-11-01T19:02:21.422Z"),
			"lastHeartbeatRecv" : ISODate("2019-11-01T19:02:21.422Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "",
			"syncingTo" : "db1:27017",
			"syncSourceHost" : "db1:27017",
			"syncSourceId" : 0,
			"infoMessage" : "",
			"configVersion" : 1
		},
		{
			"_id" : 2,
			"name" : "m3:27017",
			"ip" : "172.31.17.103",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 101903,
			"optime" : {
				"ts" : Timestamp(1572634941, 1),
				"t" : NumberLong(1)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572634941, 1),
				"t" : NumberLong(1)
			},
			"optimeDate" : ISODate("2019-11-01T19:02:21.422Z"),
			"optimeDurableDate" : ISODate("2019-11-01T19:02:21.205Z"),
			"lastHeartbeat" : ISODate("2019-11-01T19:02:21.205Z"),
			"lastHeartbeatRecv" : ISODate("2019-11-01T19:02:21.205Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "",
			"syncingTo" : "db1:27017",
			"syncSourceHost" : "db1:27017",
			"syncSourceId" : 0,
			"infoMessage" : "",
			"configVersion" : 1
		}
	],
	"ok" : 1,
	"$clusterTime" : {
		"clusterTime" : Timestamp(1572634941, 1),
		"signature" : {
			"hash" : BinData(0,"AAAAAAAAAAAAAAAAAAAAAAAAAAA="),
			"keyId" : NumberLong(0)
		}
	},
	"operationTime" : Timestamp(1572634941, 1)
}
