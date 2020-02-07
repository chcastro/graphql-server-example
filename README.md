And try the following query

{
  post(id: 1) {
    title
    description
    author {
      name
      age
    }
  },
  posts {
    title
    description
    author {
      name
      age
    }
  }
}
