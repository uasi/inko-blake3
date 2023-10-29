# inko-blake3

A BLAKE3 hasher for the Inko programming language.

## Examples

    import blake3.Blake3

    let hasher = Blake3.new
    hasher.write('hello'.to_byte_array')
    hasher.finish.to_string # => 'ea8f163db38682925e4491c5e58d4bb3506ef8c14eb78a86e908c5624a67200f'
