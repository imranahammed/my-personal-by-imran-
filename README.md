Few commad : ❤️


1. Free space ck 
df -Th

2. Node running List
ls

3. 
pgrep -f nubit-node


4. 
pgrep -f hubble

5.  Up time 
docker ps

6. 
docker logs -f df3bb1778c56

7. uptime  farcaster
docker ps

8. farcaster up time : 
START_TIME=$(docker inspect -f '{{.State.StartedAt}}' hubble-hubble-1)
CURRENT_TIME=$(date -u +"%Y-%m-%dT%H:%M:%SZ")
UPTIME_HOURS=$(echo $(( ($(date -ud "$CURRENT_TIME" +%s) - $(date -ud "$START_TIME" +%s)) / 3600 )))
echo "Uptime: $UPTIME_HOURS hours"

.
