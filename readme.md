yarn  add jest @types/jest ts-jest -D
yarn  add @types/supertest -D

yarn jest --init

// jest.config
preset: "ts-jest",

 // The glob patterns Jest uses to detect test files
  testMatch: [
     "**/__tests__/**/*.[jt]s?(x)",
     "**/?(*.)+(spec|test).[tj]s?(x)"
  ],



