# Sonic_Pi_folder-challenges
live_loop :horror_ambiance2 do
  6.times do
    sample :ambi_choir , amp: 2, beat_stretch: 14
    sleep 5
  end
  stop
end
