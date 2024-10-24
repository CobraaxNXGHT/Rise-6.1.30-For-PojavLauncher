# Rise-6.1.30-For-PojavLauncher
Latest rise (6.1.30 as of now) running on PojavLauncher with over 150 plus fps!

This works with PojavLauncher Zenith Horizon only ( I think only because I dont use the original)
for the love of christ don't dmca this, im begging yall
jvm arguement without an fps boost: -noverify -XX:+DisableAttachMechanism
with the fps boost: -noverify -Xmx900M -Xms900M -Xmn128m -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+UseNUMA -XX:+CMSParallelRemarkEnabled -XX:MaxTenuringThreshold=15 -XX:MaxGCPauseMillis=30 -XX:GCPauseIntervalMillis=150 -XX:+UseAdaptiveGCBoundary -XX:-UseGCOverheadLimit -XX:+UseBiasedLocking -XX:SurvivorRatio=8 -XX:TargetSurvivorRatio=90 -XX:MaxTenuringThreshold=15 -Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:+UseFastAccessorMethods -XX:+UseCompressedOops -XX:+OptimizeStringConcat -XX:+AggressiveOpts -XX:ReservedCodeCacheSize=2048m -XX:+UseCodeCacheFlushing -XX:SoftRefLRUPolicyMSPerMB=2000 -XX:ParallelGCThreads=10 -XX+DisableAttachMechanism
