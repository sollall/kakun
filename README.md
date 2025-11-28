# 家訓

flowchart TD
  Start((人生))
  Start --> igakubu{医学部に行けるか}
  igakubu --> |yes| Doctor[医者になる]
  igakubu --> |no| kyutei{旧帝 or 早慶以上の数学学部 / 物理学部にいけるか}
  kyutei -->|yes| Finance[金融専門職になる]
  kyutei -->|no| license{国家資格が取れるか}
  license -->|yes| kaikei[公認会計士等になる]
  license -->|no| bank[銀行に就職して客のビジネスをパクって起業する]
