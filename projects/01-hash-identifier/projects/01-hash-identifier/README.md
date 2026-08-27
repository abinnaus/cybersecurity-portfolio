# Hash Identifier

Status: In progress

Source reference:
- https://github.com/CarterPerez-dev/Cybersecurity-Projects/tree/main/PROJECTS/foundations/hash-identifier

## Overview

This project focuses on identifying common hash formats from visible characteristics such as length, character set, and known prefixes. Hash identification is a useful first step in password security analysis, forensic review, and understanding how stored credentials are represented.

## Skills Demonstrated

- Python scripting
- Command-line tool usage
- Hash format recognition
- Security documentation
- Basic cryptography concepts

## Security Context

Hashing is commonly used to store password fingerprints instead of plaintext passwords. Different algorithms and formats have recognizable patterns. For example, a 32-character hexadecimal value may indicate MD5, while strings beginning with `$2b$` commonly indicate bcrypt.

This project does not crack passwords. The purpose is to identify likely hash formats and understand why certain patterns matter.

## Planned Work

- Review the project documentation and learning modules.
- Run the tool against safe demo hashes.
- Compare MD5, SHA-256, bcrypt, and Argon2id examples.
- Document observed output and explain the results.
- Add screenshots or terminal output after testing.

## Example Inputs

| Input Pattern | Likely Format | Reason |
|---|---|---|
| `5f4dcc3b5aa765d61d8327deb882cf99` | MD5 | 32 hexadecimal characters |
| `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | SHA-256 | 64 hexadecimal characters |
| `$2b$12$...` | bcrypt | Known bcrypt prefix |

## Results

Results will be added after running the project locally.

## Lessons Learned

To be completed after implementation and testing.

## Next Improvements

- Add more hash examples.
- Compare identification confidence levels.
- Document common mistakes when copying hashes that contain special characters.
