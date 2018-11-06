# To use this on mac:

` $ nasm -f macho64 "yourFileName" `

` $ ld -macosx_version_min 10.7.0 -lSystem -o "scriptName" "yourFileName".o `

` $ ./"scriptName" `