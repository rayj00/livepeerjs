# Snapshot report for `src/index.test.js`

The actual snapshot is saved in `index.test.js.snap`.

Generated by [AVA](https://ava.li).

## AccountQuery

> Snapshot 1

    {
      data: {
        account: {
          broadcaster: {
            deposit: '1000',
            id: '0x2222222222222222222222222222222222222222',
            withdrawBlock: '50',
          },
          delegator: {
            bondedAmount: '0',
            delegateAddress: '0x1111111111111111111111111111111111111111',
            delegatedAmount: '0',
            fees: '0',
            id: '0x2222222222222222222222222222222222222222',
            lastClaimRound: '0',
            startRound: '0',
            status: 'Unbonded',
            withdrawRound: '0',
          },
          ethBalance: '1000000000',
          id: '0x2222222222222222222222222222222222222222',
          tokenBalance: '9999999999',
          transcoder: {
            active: true,
            blockRewardCut: '0',
            feeShare: '0',
            id: '0x2222222222222222222222222222222222222222',
            lastRewardRound: '0',
            pendingBlockRewardCut: '0',
            pendingFeeShare: '0',
            pendingPricePerSegment: '0',
            pricePerSegment: '0',
            status: 'Registered',
          },
        },
      },
    }

## BroadcasterQuery

> Snapshot 1

    {
      data: {
        broadcaster: {
          deposit: '1000',
          id: '0x2222222222222222222222222222222222222222',
          withdrawBlock: '50',
        },
      },
    }

## BroadcasterQuery (include jobs using skip/limit args)

> Snapshot 1

    {
      data: {
        broadcaster: {
          deposit: '1000',
          id: '0x2222222222222222222222222222222222222222',
          jobs: [
            {
              broadcaster: '0x2222222222222222222222222222222222222222',
              id: '2',
              profiles: [
                {
                  bitrate: '1200k',
                  framerate: 30,
                  id: '93c717e7',
                  name: 'P360p30fps16x9',
                  resolution: '640x360',
                },
                {
                  bitrate: '3500k',
                  framerate: 30,
                  id: '79332fe7',
                  name: 'P720p30fps4x3',
                  resolution: '960x720',
                },
                {
                  bitrate: '1500k',
                  framerate: 30,
                  id: '5ecf4b52',
                  name: 'P576p30fps16x9',
                  resolution: '1024x576',
                },
              ],
              streamId: 'baz',
            },
          ],
          withdrawBlock: '50',
        },
      },
    }

## BroadcasterQuery (include jobs)

> Snapshot 1

    {
      data: {
        broadcaster: {
          deposit: '1000',
          id: '0x2222222222222222222222222222222222222222',
          jobs: [
            {
              broadcaster: '0x2222222222222222222222222222222222222222',
              id: '3',
              profiles: [],
              streamId: 'baz',
            },
            {
              broadcaster: '0x2222222222222222222222222222222222222222',
              id: '2',
              profiles: [
                {
                  bitrate: '1200k',
                  framerate: 30,
                  id: '93c717e7',
                  name: 'P360p30fps16x9',
                  resolution: '640x360',
                },
                {
                  bitrate: '3500k',
                  framerate: 30,
                  id: '79332fe7',
                  name: 'P720p30fps4x3',
                  resolution: '960x720',
                },
                {
                  bitrate: '1500k',
                  framerate: 30,
                  id: '5ecf4b52',
                  name: 'P576p30fps16x9',
                  resolution: '1024x576',
                },
              ],
              streamId: 'baz',
            },
            {
              broadcaster: '0x2222222222222222222222222222222222222222',
              id: '1',
              profiles: [
                {
                  bitrate: '400k',
                  framerate: 30,
                  id: 'fca40bf9',
                  name: 'P144p30fps16x9',
                  resolution: '256x144',
                },
                {
                  bitrate: '600k',
                  framerate: 30,
                  id: 'c0a6517a',
                  name: 'P240p30fps16x9',
                  resolution: '426x240',
                },
              ],
              streamId: 'x36xhzz',
            },
          ],
          withdrawBlock: '50',
        },
      },
    }

## DelegatorQuery

> Snapshot 1

    {
      data: {
        delegator: {
          bondedAmount: '0',
          delegateAddress: '0x1111111111111111111111111111111111111111',
          delegatedAmount: '0',
          fees: '0',
          id: '0x2222222222222222222222222222222222222222',
          lastClaimRound: '0',
          startRound: '0',
          status: 'Unbonded',
          withdrawRound: '0',
        },
      },
    }

## JobQuery

> Snapshot 1

    {
      data: {
        job: {
          broadcaster: '0x1111111111111111111111111111111111111111',
          id: '0',
          profiles: [
            {
              bitrate: '400k',
              framerate: 30,
              id: 'fca40bf9',
              name: 'P144p30fps16x9',
              resolution: '256x144',
            },
          ],
          streamId: 'x36xhzz',
        },
      },
    }

## JobsQuery

> Snapshot 1

    {
      data: {
        jobs: [
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '3',
            profiles: [],
            streamId: 'baz',
          },
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '2',
            profiles: [
              {
                bitrate: '1200k',
                framerate: 30,
                id: '93c717e7',
                name: 'P360p30fps16x9',
                resolution: '640x360',
              },
              {
                bitrate: '3500k',
                framerate: 30,
                id: '79332fe7',
                name: 'P720p30fps4x3',
                resolution: '960x720',
              },
              {
                bitrate: '1500k',
                framerate: 30,
                id: '5ecf4b52',
                name: 'P576p30fps16x9',
                resolution: '1024x576',
              },
            ],
            streamId: 'baz',
          },
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '1',
            profiles: [
              {
                bitrate: '400k',
                framerate: 30,
                id: 'fca40bf9',
                name: 'P144p30fps16x9',
                resolution: '256x144',
              },
              {
                bitrate: '600k',
                framerate: 30,
                id: 'c0a6517a',
                name: 'P240p30fps16x9',
                resolution: '426x240',
              },
            ],
            streamId: 'x36xhzz',
          },
          {
            broadcaster: '0x1111111111111111111111111111111111111111',
            id: '0',
            profiles: [
              {
                bitrate: '400k',
                framerate: 30,
                id: 'fca40bf9',
                name: 'P144p30fps16x9',
                resolution: '256x144',
              },
            ],
            streamId: 'x36xhzz',
          },
        ],
      },
    }

## JobsQuery (broadcaster arg)

> Snapshot 1

    {
      data: {
        jobs: [
          {
            broadcaster: '0x1111111111111111111111111111111111111111',
            id: '0',
            profiles: [
              {
                bitrate: '400k',
                framerate: 30,
                id: 'fca40bf9',
                name: 'P144p30fps16x9',
                resolution: '256x144',
              },
            ],
            streamId: 'x36xhzz',
          },
        ],
      },
    }

## JobsQuery (limit arg)

> Snapshot 1

    {
      data: {
        jobs: [
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '3',
            profiles: [],
            streamId: 'baz',
          },
        ],
      },
    }

## JobsQuery (skip / limit args)

> Snapshot 1

    {
      data: {
        jobs: [
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '2',
            profiles: [
              {
                bitrate: '1200k',
                framerate: 30,
                id: '93c717e7',
                name: 'P360p30fps16x9',
                resolution: '640x360',
              },
              {
                bitrate: '3500k',
                framerate: 30,
                id: '79332fe7',
                name: 'P720p30fps4x3',
                resolution: '960x720',
              },
              {
                bitrate: '1500k',
                framerate: 30,
                id: '5ecf4b52',
                name: 'P576p30fps16x9',
                resolution: '1024x576',
              },
            ],
            streamId: 'baz',
          },
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '1',
            profiles: [
              {
                bitrate: '400k',
                framerate: 30,
                id: 'fca40bf9',
                name: 'P144p30fps16x9',
                resolution: '256x144',
              },
              {
                bitrate: '600k',
                framerate: 30,
                id: 'c0a6517a',
                name: 'P240p30fps16x9',
                resolution: '426x240',
              },
            ],
            streamId: 'x36xhzz',
          },
          {
            broadcaster: '0x1111111111111111111111111111111111111111',
            id: '0',
            profiles: [
              {
                bitrate: '400k',
                framerate: 30,
                id: 'fca40bf9',
                name: 'P144p30fps16x9',
                resolution: '256x144',
              },
            ],
            streamId: 'x36xhzz',
          },
        ],
      },
    }

## JobsQuery (skip arg)

> Snapshot 1

    {
      data: {
        jobs: [
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '2',
            profiles: [
              {
                bitrate: '1200k',
                framerate: 30,
                id: '93c717e7',
                name: 'P360p30fps16x9',
                resolution: '640x360',
              },
              {
                bitrate: '3500k',
                framerate: 30,
                id: '79332fe7',
                name: 'P720p30fps4x3',
                resolution: '960x720',
              },
              {
                bitrate: '1500k',
                framerate: 30,
                id: '5ecf4b52',
                name: 'P576p30fps16x9',
                resolution: '1024x576',
              },
            ],
            streamId: 'baz',
          },
          {
            broadcaster: '0x2222222222222222222222222222222222222222',
            id: '1',
            profiles: [
              {
                bitrate: '400k',
                framerate: 30,
                id: 'fca40bf9',
                name: 'P144p30fps16x9',
                resolution: '256x144',
              },
              {
                bitrate: '600k',
                framerate: 30,
                id: 'c0a6517a',
                name: 'P240p30fps16x9',
                resolution: '426x240',
              },
            ],
            streamId: 'x36xhzz',
          },
          {
            broadcaster: '0x1111111111111111111111111111111111111111',
            id: '0',
            profiles: [
              {
                bitrate: '400k',
                framerate: 30,
                id: 'fca40bf9',
                name: 'P144p30fps16x9',
                resolution: '256x144',
              },
            ],
            streamId: 'x36xhzz',
          },
        ],
      },
    }

## TranscoderQuery

> Snapshot 1

    {
      data: {
        transcoder: {
          active: true,
          blockRewardCut: '0',
          feeShare: '0',
          id: '0x2222222222222222222222222222222222222222',
          lastRewardRound: '0',
          pendingBlockRewardCut: '0',
          pendingFeeShare: '0',
          pendingPricePerSegment: '0',
          pricePerSegment: '0',
          status: 'Registered',
        },
      },
    }
