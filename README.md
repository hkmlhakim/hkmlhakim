input = {
    "image": "https://github.com/hkmlhakim/hkmlhakim/assets/164167010/74b26ff3-407f-41aa-8ea2-c37df950c078",
    "style": "Pixel",
    "prompt": "a person in a post apocalyptic war game",
    "instant_id_strength": 0.8
}

output = replicate.run(
    "fofr/face-to-many:35cea9c3164d9fb7fbd48b51503eabdb39c9d04fdaef9a68f368bed8087ec5f9",
    input=input
)
print(output)
#=>
