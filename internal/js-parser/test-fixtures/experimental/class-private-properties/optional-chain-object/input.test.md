# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-properties > optional-chain-object`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/class-private-properties/optional-chain-object/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/class-private-properties/optional-chain-object/input.js"
		end: Object {
			column: 0
			line: 15
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "experimental/class-private-properties/optional-chain-object/input.js"
					identifierName: "Foo"
					end: Object {
						column: 9
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "experimental/class-private-properties/optional-chain-object/input.js"
				end: Object {
					column: 1
					line: 14
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "experimental/class-private-properties/optional-chain-object/input.js"
					end: Object {
						column: 1
						line: 14
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "experimental/class-private-properties/optional-chain-object/input.js"
									identifierName: "x"
									end: Object {
										column: 11
										line: 2
									}
									start: Object {
										column: 10
										line: 2
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 11
									line: 2
								}
								start: Object {
									column: 9
									line: 2
								}
							}
						}
						value: JSNumericLiteral {
							value: 1
							format: undefined
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 15
									line: 2
								}
								start: Object {
									column: 14
									line: 2
								}
							}
						}
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-private-properties/optional-chain-object/input.js"
							end: Object {
								column: 16
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 2
							}
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 11
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
						}
					}
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "m"
								loc: Object {
									filename: "experimental/class-private-properties/optional-chain-object/input.js"
									identifierName: "m"
									end: Object {
										column: 11
										line: 3
									}
									start: Object {
										column: 10
										line: 3
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 11
									line: 3
								}
								start: Object {
									column: 9
									line: 3
								}
							}
						}
						value: JSFunctionExpression {
							id: undefined
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 27
									line: 3
								}
								start: Object {
									column: 14
									line: 3
								}
							}
							body: JSBlockStatement {
								body: Array []
								directives: Array []
								loc: Object {
									filename: "experimental/class-private-properties/optional-chain-object/input.js"
									end: Object {
										column: 27
										line: 3
									}
									start: Object {
										column: 25
										line: 3
									}
								}
							}
							head: JSFunctionHead {
								async: false
								generator: false
								hasHoistedVars: false
								params: Array []
								rest: undefined
								returnType: undefined
								thisType: undefined
								typeParameters: undefined
								loc: Object {
									filename: "experimental/class-private-properties/optional-chain-object/input.js"
									end: Object {
										column: 24
										line: 3
									}
									start: Object {
										column: 22
										line: 3
									}
								}
							}
						}
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-private-properties/optional-chain-object/input.js"
							end: Object {
								column: 28
								line: 3
							}
							start: Object {
								column: 2
								line: 3
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 3
							}
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 11
									line: 3
								}
								start: Object {
									column: 2
									line: 3
								}
							}
						}
					}
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: Object {
									filename: "experimental/class-private-properties/optional-chain-object/input.js"
									identifierName: "test"
									end: Object {
										column: 13
										line: 5
									}
									start: Object {
										column: 9
										line: 5
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 13
									line: 5
								}
								start: Object {
									column: 9
									line: 5
								}
							}
						}
						loc: Object {
							filename: "experimental/class-private-properties/optional-chain-object/input.js"
							end: Object {
								column: 3
								line: 13
							}
							start: Object {
								column: 2
								line: 5
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 15
									line: 5
								}
								start: Object {
									column: 13
									line: 5
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 5
							}
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 13
									line: 5
								}
								start: Object {
									column: 2
									line: 5
								}
							}
						}
						body: JSBlockStatement {
							directives: Array []
							loc: Object {
								filename: "experimental/class-private-properties/optional-chain-object/input.js"
								end: Object {
									column: 3
									line: 13
								}
								start: Object {
									column: 16
									line: 5
								}
							}
							body: Array [
								JSVariableDeclarationStatement {
									loc: Object {
										filename: "experimental/class-private-properties/optional-chain-object/input.js"
										end: Object {
											column: 27
											line: 6
										}
										start: Object {
											column: 4
											line: 6
										}
									}
									declaration: JSVariableDeclaration {
										kind: "const"
										loc: Object {
											filename: "experimental/class-private-properties/optional-chain-object/input.js"
											end: Object {
												column: 27
												line: 6
											}
											start: Object {
												column: 4
												line: 6
											}
										}
										declarations: Array [
											JSVariableDeclarator {
												id: JSBindingIdentifier {
													name: "o"
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														identifierName: "o"
														end: Object {
															column: 11
															line: 6
														}
														start: Object {
															column: 10
															line: 6
														}
													}
												}
												loc: Object {
													filename: "experimental/class-private-properties/optional-chain-object/input.js"
													end: Object {
														column: 26
														line: 6
													}
													start: Object {
														column: 10
														line: 6
													}
												}
												init: JSObjectExpression {
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														end: Object {
															column: 26
															line: 6
														}
														start: Object {
															column: 14
															line: 6
														}
													}
													properties: Array [
														JSObjectProperty {
															key: JSStaticPropertyKey {
																value: JSIdentifier {
																	name: "Foo"
																	loc: Object {
																		filename: "experimental/class-private-properties/optional-chain-object/input.js"
																		identifierName: "Foo"
																		end: Object {
																			column: 19
																			line: 6
																		}
																		start: Object {
																			column: 16
																			line: 6
																		}
																	}
																}
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	end: Object {
																		column: 19
																		line: 6
																	}
																	start: Object {
																		column: 16
																		line: 6
																	}
																}
															}
															value: JSReferenceIdentifier {
																name: "Foo"
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	identifierName: "Foo"
																	end: Object {
																		column: 24
																		line: 6
																	}
																	start: Object {
																		column: 21
																		line: 6
																	}
																}
															}
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																end: Object {
																	column: 24
																	line: 6
																}
																start: Object {
																	column: 16
																	line: 6
																}
															}
														}
													]
												}
											}
										]
									}
								}
								JSReturnStatement {
									loc: Object {
										filename: "experimental/class-private-properties/optional-chain-object/input.js"
										end: Object {
											column: 6
											line: 12
										}
										start: Object {
											column: 4
											line: 7
										}
									}
									argument: JSArrayExpression {
										loc: Object {
											filename: "experimental/class-private-properties/optional-chain-object/input.js"
											end: Object {
												column: 5
												line: 12
											}
											start: Object {
												column: 11
												line: 7
											}
										}
										elements: Array [
											JSMemberExpression {
												loc: Object {
													filename: "experimental/class-private-properties/optional-chain-object/input.js"
													end: Object {
														column: 15
														line: 8
													}
													start: Object {
														column: 6
														line: 8
													}
												}
												property: JSStaticMemberProperty {
													value: JSPrivateName {
														id: JSIdentifier {
															name: "x"
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																identifierName: "x"
																end: Object {
																	column: 15
																	line: 8
																}
																start: Object {
																	column: 14
																	line: 8
																}
															}
														}
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															end: Object {
																column: 15
																line: 8
															}
															start: Object {
																column: 13
																line: 8
															}
														}
													}
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														end: Object {
															column: 15
															line: 8
														}
														start: Object {
															column: 13
															line: 8
														}
													}
												}
												object: JSMemberExpression {
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														end: Object {
															column: 12
															line: 8
														}
														start: Object {
															column: 6
															line: 8
														}
													}
													object: JSReferenceIdentifier {
														name: "o"
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															identifierName: "o"
															end: Object {
																column: 7
																line: 8
															}
															start: Object {
																column: 6
																line: 8
															}
														}
													}
													property: JSStaticMemberProperty {
														value: JSIdentifier {
															name: "Foo"
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																identifierName: "Foo"
																end: Object {
																	column: 12
																	line: 8
																}
																start: Object {
																	column: 9
																	line: 8
																}
															}
														}
														optional: true
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															identifierName: "Foo"
															end: Object {
																column: 12
																line: 8
															}
															start: Object {
																column: 9
																line: 8
															}
														}
													}
												}
											}
											JSMemberExpression {
												loc: Object {
													filename: "experimental/class-private-properties/optional-chain-object/input.js"
													end: Object {
														column: 23
														line: 9
													}
													start: Object {
														column: 6
														line: 9
													}
												}
												property: JSStaticMemberProperty {
													value: JSIdentifier {
														name: "toFixed"
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															identifierName: "toFixed"
															end: Object {
																column: 23
																line: 9
															}
															start: Object {
																column: 16
																line: 9
															}
														}
													}
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														identifierName: "toFixed"
														end: Object {
															column: 23
															line: 9
														}
														start: Object {
															column: 16
															line: 9
														}
													}
												}
												object: JSMemberExpression {
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														end: Object {
															column: 15
															line: 9
														}
														start: Object {
															column: 6
															line: 9
														}
													}
													property: JSStaticMemberProperty {
														value: JSPrivateName {
															id: JSIdentifier {
																name: "x"
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	identifierName: "x"
																	end: Object {
																		column: 15
																		line: 9
																	}
																	start: Object {
																		column: 14
																		line: 9
																	}
																}
															}
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																end: Object {
																	column: 15
																	line: 9
																}
																start: Object {
																	column: 13
																	line: 9
																}
															}
														}
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															end: Object {
																column: 15
																line: 9
															}
															start: Object {
																column: 13
																line: 9
															}
														}
													}
													object: JSMemberExpression {
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															end: Object {
																column: 12
																line: 9
															}
															start: Object {
																column: 6
																line: 9
															}
														}
														object: JSReferenceIdentifier {
															name: "o"
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																identifierName: "o"
																end: Object {
																	column: 7
																	line: 9
																}
																start: Object {
																	column: 6
																	line: 9
																}
															}
														}
														property: JSStaticMemberProperty {
															value: JSIdentifier {
																name: "Foo"
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	identifierName: "Foo"
																	end: Object {
																		column: 12
																		line: 9
																	}
																	start: Object {
																		column: 9
																		line: 9
																	}
																}
															}
															optional: true
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																identifierName: "Foo"
																end: Object {
																	column: 12
																	line: 9
																}
																start: Object {
																	column: 9
																	line: 9
																}
															}
														}
													}
												}
											}
											JSOptionalCallExpression {
												loc: Object {
													filename: "experimental/class-private-properties/optional-chain-object/input.js"
													end: Object {
														column: 26
														line: 10
													}
													start: Object {
														column: 6
														line: 10
													}
												}
												arguments: Array [
													JSNumericLiteral {
														value: 2
														format: undefined
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															end: Object {
																column: 25
																line: 10
															}
															start: Object {
																column: 24
																line: 10
															}
														}
													}
												]
												callee: JSMemberExpression {
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														end: Object {
															column: 23
															line: 10
														}
														start: Object {
															column: 6
															line: 10
														}
													}
													property: JSStaticMemberProperty {
														value: JSIdentifier {
															name: "toFixed"
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																identifierName: "toFixed"
																end: Object {
																	column: 23
																	line: 10
																}
																start: Object {
																	column: 16
																	line: 10
																}
															}
														}
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															identifierName: "toFixed"
															end: Object {
																column: 23
																line: 10
															}
															start: Object {
																column: 16
																line: 10
															}
														}
													}
													object: JSMemberExpression {
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															end: Object {
																column: 15
																line: 10
															}
															start: Object {
																column: 6
																line: 10
															}
														}
														property: JSStaticMemberProperty {
															value: JSPrivateName {
																id: JSIdentifier {
																	name: "x"
																	loc: Object {
																		filename: "experimental/class-private-properties/optional-chain-object/input.js"
																		identifierName: "x"
																		end: Object {
																			column: 15
																			line: 10
																		}
																		start: Object {
																			column: 14
																			line: 10
																		}
																	}
																}
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	end: Object {
																		column: 15
																		line: 10
																	}
																	start: Object {
																		column: 13
																		line: 10
																	}
																}
															}
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																end: Object {
																	column: 15
																	line: 10
																}
																start: Object {
																	column: 13
																	line: 10
																}
															}
														}
														object: JSMemberExpression {
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																end: Object {
																	column: 12
																	line: 10
																}
																start: Object {
																	column: 6
																	line: 10
																}
															}
															object: JSReferenceIdentifier {
																name: "o"
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	identifierName: "o"
																	end: Object {
																		column: 7
																		line: 10
																	}
																	start: Object {
																		column: 6
																		line: 10
																	}
																}
															}
															property: JSStaticMemberProperty {
																value: JSIdentifier {
																	name: "Foo"
																	loc: Object {
																		filename: "experimental/class-private-properties/optional-chain-object/input.js"
																		identifierName: "Foo"
																		end: Object {
																			column: 12
																			line: 10
																		}
																		start: Object {
																			column: 9
																			line: 10
																		}
																	}
																}
																optional: true
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	identifierName: "Foo"
																	end: Object {
																		column: 12
																		line: 10
																	}
																	start: Object {
																		column: 9
																		line: 10
																	}
																}
															}
														}
													}
												}
											}
											JSOptionalCallExpression {
												arguments: Array []
												loc: Object {
													filename: "experimental/class-private-properties/optional-chain-object/input.js"
													end: Object {
														column: 17
														line: 11
													}
													start: Object {
														column: 6
														line: 11
													}
												}
												callee: JSMemberExpression {
													loc: Object {
														filename: "experimental/class-private-properties/optional-chain-object/input.js"
														end: Object {
															column: 15
															line: 11
														}
														start: Object {
															column: 6
															line: 11
														}
													}
													property: JSStaticMemberProperty {
														value: JSPrivateName {
															id: JSIdentifier {
																name: "m"
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	identifierName: "m"
																	end: Object {
																		column: 15
																		line: 11
																	}
																	start: Object {
																		column: 14
																		line: 11
																	}
																}
															}
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																end: Object {
																	column: 15
																	line: 11
																}
																start: Object {
																	column: 13
																	line: 11
																}
															}
														}
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															end: Object {
																column: 15
																line: 11
															}
															start: Object {
																column: 13
																line: 11
															}
														}
													}
													object: JSMemberExpression {
														loc: Object {
															filename: "experimental/class-private-properties/optional-chain-object/input.js"
															end: Object {
																column: 12
																line: 11
															}
															start: Object {
																column: 6
																line: 11
															}
														}
														object: JSReferenceIdentifier {
															name: "o"
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																identifierName: "o"
																end: Object {
																	column: 7
																	line: 11
																}
																start: Object {
																	column: 6
																	line: 11
																}
															}
														}
														property: JSStaticMemberProperty {
															value: JSIdentifier {
																name: "Foo"
																loc: Object {
																	filename: "experimental/class-private-properties/optional-chain-object/input.js"
																	identifierName: "Foo"
																	end: Object {
																		column: 12
																		line: 11
																	}
																	start: Object {
																		column: 9
																		line: 11
																	}
																}
															}
															optional: true
															loc: Object {
																filename: "experimental/class-private-properties/optional-chain-object/input.js"
																identifierName: "Foo"
																end: Object {
																	column: 12
																	line: 11
																}
																start: Object {
																	column: 9
																	line: 11
																}
															}
														}
													}
												}
											}
										]
									}
								}
							]
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
